Для выбора оверлея определеть одно из
```cpp
#define DISCORD
#define MUMBLE
#define WINDOW  // только fullscreen windowed
```

Сборка
```shell
cmake -B build -S . -A x64 -DCMAKE_BUILD_TYPE=Release
```
```shell
cmake --build build --config Release
```

Параметры запуска (для discord/mumle оверлея)
```
-allow_third_party_software -sw
```
