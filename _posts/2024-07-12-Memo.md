### Path

- **TaskBar**
- %APPDATA%\Microsoft\Internet Explorer\Quick Launch\User Pinned\TaskBar

- **Host**
- c:\windows\system32\drivers\etc

- **TimeColor**

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize

### Command

#### Redis:

- 添加服务：redis-server --service-install redis.windows-service.conf --loglevel verbose
- 卸载服务：redis-server --service-uninstall
- 开启服务：redis-server --service-start
- 停止服务：redis-server --service-stop

#### Adb:

- adb devices
- adb tcpid [port]
- adb connect [ip]
