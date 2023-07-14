1. Daj swojemu użytkownikowi "szkolenie" uprawnienia do używania polecenia sudo
2. Zaktualizuj system, użyj menagera pakietów dnf a po aktualizacji sprawdź w menagerze dnf czy jakaś aktualizacja pozostała do wykonania.
   
  `check-update`
   
3. Sprawdź jaki pakiet zawiera program który pozwoli Ci sprawdzić czy musisz wykonać restart systemu po aktualizacji i zainstaluj go
   
```bash
   dnf needs-restarting
```
   
4. Sprawdź czy musisz wykonać restart systemu
5. Zainstaluj pakiet mc
6. Sprawdź komendą man opis programu mc
7. Sprawdź stronę pomocy za pomocą polecenia man dla pakietu mc
8. Sprawdź jakie serwisy są uruchomione w systemie
   
   Systemctl
   
9. Sprawdź status serwisu firewall oraz ssh
10. Sprawdź plik konfiguracyjny SSH i zobacz na jakim porcie działa twoja usługa SSH
11. Sprawdź do jakich subskrypcji masz dostęp w systemie RHEL

```
subscription-manager list --available
```