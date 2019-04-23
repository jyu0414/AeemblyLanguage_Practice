# AssemblyLanguage_Practice
アセンブリ言語の勉強

#環境
macOS 10.14（64bit）で確認
x86 64bit用
nasm（x86用オープンソースアセンブラ）を使用

#使い方
 $ nasm -f macho64 filename.asm
 $ ld -lSystem -macosx_version_min 10.13 filename.o
 $ ./filename.out