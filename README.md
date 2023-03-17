# Filius-Router

Il server DHCP ha il compito di assegnare ad un dispositivo che si connette alla rete il primo indirizzo IP valido disponibile tra quelli che sono stati definiti nei parametri di configurazione.

Inizialmente i PC delle due reti non si raggiungevano con ping perché non era stato inserito il default gateway, che si occupa dell'instradamento dei pacchetti verso la rete esterna, nel nostro caso abbiamo inserito il router come default gateway.

Il protocollo utilizzato dal comando ping è il ICMP (Internet Control Message Protocol) è un protocollo di servizio per reti che fornisce informazioni relative allo stato e messaggi di errore.
