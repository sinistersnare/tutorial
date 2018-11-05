Git jest "systemem kontroli wersji", którego używa wielu programistów. Program ten śledzi zmiany w plikach na przestrzeni czasu, dzięki czemu możesz później przywracać wybrane wersje tych plików. A bit like the "track changes" feature in word processor programs (e.g., Microsoft Word or LibreOffice Writer), but much more powerful.

## Instalacja Gita

<!--sec data-title="Installing Git: Windows" data-id="git_install_windows"
data-collapse=true ces-->

Możesz ściągnąć Gita z [git-scm.com](https://git-scm.com/). You can hit "next" on all steps except for two: in the step where it asks to choose your editor, you should pick Nano, and in the step entitled "Adjusting your PATH environment", choose "Use Git and optional Unix tools from the Windows Command Prompt" (the bottom option). Poza tym domyślne ustawienia są w porządku. Upewnij się jeszcze, że w kroku "Configuring the line ending conversions" wybrana jest opcja "Checkout Windows-style, commit Unix-style line endings".

Nie zapomnij zrestartować wiersza polecenia lub Powershell po instalacji zakończonej sukcesem. <!--endsec-->

<!--sec data-title="Installing Git: OS X" data-id="git_install_OSX"
data-collapse=true ces-->

Ściągnij Gita z [git-scm.com](https://git-scm.com/) i postępuj zgodnie z instrukcją.

> **Uwaga**Jeżeli działasz na OS X 10.6, 10.7 lub 10.8, będziesz musiała zainstalować wersję gita dostępną tutaj: [Git installer for OS X Snow Leopard](https://sourceforge.net/projects/git-osx-installer/files/git-2.3.5-intel-universal-snow-leopard.dmg/download)

<!--endsec-->

<!--sec data-title="Installing Git: Debian or Ubuntu" data-id="git_install_debian_ubuntu"
data-collapse=true ces-->

{% filename %}command-line{% endfilename %}

```bash
sudo apt install git
```

<!--endsec-->

<!--sec data-title="Installing Git: Fedora" data-id="git_install_fedora"
data-collapse=true ces-->

{% filename %}command-line{% endfilename %}

```bash
sudo dnf install git
```

<!--endsec-->

<!--sec data-title="Installing Git: openSUSE" data-id="git_install_openSUSE"
data-collapse=true ces-->

{% filename %}command-line{% endfilename %}

```bash
sudo zypper install git
```

<!--endsec-->