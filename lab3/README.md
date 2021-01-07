Lab 3a
------

Pomoci ansible vetsinou spravujeme vice nez jeden server a malokdy maji vsechny servery uplne stejnou konfiguraci. V tomto labu mame 2 servery, kde na jednom pobezi ruzne weby. Inspirujte se v tomto labu a doplnte vse co jste se naucili z predchozich labu


Lab 3b
------

Vytvorte ansible konfiguraci pro nasledujici situaci

```yaml
webs:
  web1.example.infra:
  - web1.example.com
  - web2.example.com
  - web3.example.com
  web2.example.infra:
  - web4.example.com
  - web5.example.com

dbs:
  db1.example.infra

```

 * Na vsech serverech je nainstalovan vim, htop, git, tree, mc
 * Na aplikacnich serverech bezi nginx naslouchajici na definovanych uvedenych adresach
 * Na data serverech bezi mariadb server


**Aby ste toho dosahli, pouzijte host_vars a group_vars**

