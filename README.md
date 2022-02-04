# Dns_filter

# Descrizione

DNS Filter consente di bloccare le richieste dns relativi a domini non ritenuti sicuri effettuate da un dispositivo di rete. I pacchetti dns vengono inotrati in base a 2 policy: policy impostata dall'utente (policy.txt), siti web ritenuti non sicuri (blacklist-hostnames.txt)<br>
    
Il software utilizza la libreria Scapy che permette la manipolazione dei pacchetti di rete e consente di assemblare o decodificare i pacchetti di un ampio numero di protocolli, inviarli, catturarli, inoltrare richieste e risposte.
Il software utilizza un attacco di tipo Man in the middle per intercettare le comunicazioni tra un dispositivo e il gateway. L'attacco prende il nome di ARP Spoofing poichè sfrutta una vulnerabilità dell'ARP (mancanza di autenticazione), inviando ARP Reply modificate per alterare la comunicazione.
