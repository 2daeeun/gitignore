# 자주 사용하는 gitignore파일
매번 로컬에서 gitignore파일 찾는게 귀찮아서 그냥 올려둠.

### 리눅스에서 다운로드
```
wget https://raw.githubusercontent.com/2daeeun/gitignore/main/.gitignore
```

### 윈도우 PowerShell에서 다운로드
```
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/2daeeun/gitignore/main/.gitignore" -OutFile ".gitignore"
```

### 내용
```bash
# 바이너리 파일 및 실행 파일
*.out
*.o
*.obj
*.exe
*.elf
*.a
*.lib
*.so
*.dylib

# 빌드 디렉토리
/build/
/bin/
/obj/
/target/

# 자동 생성된 파일
*.d
*.dSYM
*.swp

# 리눅스 커널 디버깅 관련 파일
vmlinux
vmlinuz
*.map
System.map
Module.symvers
modules.builtin
modules.builtin.modinfo
modules.order
*.mod.c

# 커널 빌드 디렉토리
# /arch/
# /include/config/
# /include/generated/
# /scripts/
*.o.cmd
*.ko.cmd
*.mod
*.mod.o
*.mod.c
*.symvers

# 디버깅 관련
*.lst
*.lss
*.tmp
*.bak
*.orig

# gdb 관련 파일
# .gdb_history
# .gdbinit
# core

# Ignore ccls-cache directory
.ccls-cache

# Ignore ctags
tags

# 기타
*.log
*.tmp
*.bak
*.~*
*.orig
```
