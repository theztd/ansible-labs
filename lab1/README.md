Lab 1
=====

Zakladni prace s ansible a seznameni se s syntaxi. Kod ktery je zde k dispozici slouzi jako odrazovy mustek a nebojte se ho pouzit.

Ukol 1
------
Pomoci ansible nainstalujte na cisty system nginx a nahrajte vlastni html stranku. Pro deploj Html stranky vyuzijte modul template a parametrizujte alespon jeden prvek stranky (napriklad title)


Ukol 2
------
Do stranky doplnte nejaky obrazek, ktery bude deplojovan opet pomoci ansible.


Ukol 3
------
Nginx umoznuje hostovat na jednom serveru vice domen, upravte vas kod tak, aby se do adresare /etc/nginx/sites-enabled/ generovaly konfigurace novych stranek. Pouzijte k tomu predlohu vhosts.conf.j2 a nezapomente po kazdem deploji nove konfigurace reloadnout nginx.


**BONUS**
* Ansible template modul umoznuje zkontrolovat, zda je nove nasazeny soubor validni, zjistete jak a zkuste to implementovat
* Prozkoumejte moznost jak soubor nahrat na server vickrat, pomozte si dokumentaci a googlem