-Windows Server 2025 działa jako członek domeny MEDLAB. 
-Secure channel po wcześniejszym rejoinie został przywrócony i zweryfikowany względem DC01.medlab.test. 
-GPO po naprawie domeny działa poprawnie. 
-SQL Server 2025 / MSSQLSERVER działa jako default instance. 
-Zainstalowany SSMS 22 wraz z Database Projects i Git tooling. 
-Problem 18456 / State 5 został rozpoznany jako brak loginu dla lokalnego SQL01\Administrator. 
-Z konfiguracji instalacyjnej ustaliliśmy właściwego SQL sysadmina:
MEDLAB\Administrator. 
-SSMS uruchomiony przez runas z domenowym kontem. 
-Połączenie do SQL01 przez Windows Authentication działa.