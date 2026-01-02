# CSE232 Term Project

## Derleme

```bash
make clean
make
```

## Kullanım

### 1. Assembly dosyalarını derle

```bash
./assembler test_main.asm
./assembler sub.asm
./assembler data.asm
```

### 2. Object dosyalarını birleştir (Link)

```bash
./linker_exec exp test_main.o test_main.t sub.o sub.t data.o data.t
```

### 3. Executable'ı yükle ve çalıştır

```bash
./loader exp.exe exp.t
```

## Notlar

- Loader çalıştırıldığında loadpoint (yükleme adresi) ister
- Decimal (örn: `1000`) veya hex (örn: `0x1000`) formatında girebilirsiniz