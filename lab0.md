# Отчет по Лабораторной работе №0 «Создание скрипта для автоматизации установки под Windows»
## Выполнил студент: Казаковцев В.Л. Группа P3321
### 7-zip
`msiexec /i 7z1604-x64.msi INSTALLDIR="C:\Program Files\7-Zip" /passive /norestart /le "7zip-log.txt"`

### Paint.NET
`paint.net.4.2.11.Install.exe /auto "C:\Program Files\Graphics\Paint" DESKTOPSHORTCUT=1`

### Inkscape
`msiexec /i inkscape-1.0-x64.msi INSTALLDIR="C:\Program Files\Graphics\Inkscape" /qr /norestart /lw "inkscape-log.txt"`

### LibreOffice
```
msiexec /i LibreOffice_6.4.4_Win_x64.msi /passive /norestart /le "libreoffice-install-log.txt"
msiexec /i LibreOffice_6.4.4_Win_x86_helppack_ru.msi /passive /forcerestart /le+ "libreoffice-install-log.txt"
```

### Notepad++
`msiexec /i Notepad++7.6.6.msi /quiet`

### JRE
`jre-8u251-windows-x64.exe /s /L C:\Java\jre-log.txt INSTALLDIR=C:\Java\JRE WEB_ANALYTICS=Disable WEB_JAVA=Enable`
