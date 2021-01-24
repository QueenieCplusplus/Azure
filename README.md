# Azure
2020 10月做的雲端研究


* Azur CLI (1)

* Cloud Shell (or called as Power Shell) https://shell.azure.com

* Azure Portal  https://portal.azure.com/

* Private IP range and Subnetting

![private ip](https://raw.githubusercontent.com/QueenieCplusplus/QuickGoThru/master/private%20ip%20range.png)

* VM creation, config (1)

  https://docs.microsoft.com/en-us/azure/virtual-network/quick-create-portal?toc=/azure/networking/toc.json

* Connect Sec

   * RDP (1)
   
      When using RDP, remmember to add Rule to FW to allow inbound ICMP.
      
      This command allows ICMP inbound through the Windows firewall:
      
           New-NetFirewallRule –DisplayName "Allow ICMPv4-In" –Protocol ICMPv4
   
     ![rdp](https://raw.githubusercontent.com/QueenieCplusplus/QuickGoThru/master/rdp%20connection.png)

   * RDP/SSH over TLS (1)
   
      When using Bastion, Public IP is not needed.

     ![tls](https://raw.githubusercontent.com/QueenieCplusplus/QuickGoThru/master/bastion%20TLS.png)

   * VPN (encrypted connection) thru Portal, Power Shell (1), CLI

     ![vpn](https://raw.githubusercontent.com/QueenieCplusplus/QuickGoThru/master/vpn%20gw.png)

   * ExpressRoute (1)
   
       To extend on-premise network over private connection. 

   * DNS (1) 

     https://digwebinterface.com

     https://dnschecker.org/

     ![dns](https://raw.githubusercontent.com/QueenieCplusplus/QuickGoThru/master/dns.png)

     ![dns LB](https://raw.githubusercontent.com/QueenieCplusplus/QuickGoThru/master/dns%20lb.png)
     
   * Peering 

* Delivery Sec

   * LB

     ![lb tier4](https://raw.githubusercontent.com/QueenieCplusplus/QuickGoThru/master/LB%20tier4.png)

     ![lb](https://raw.githubusercontent.com/QueenieCplusplus/QuickGoThru/master/LB.png)
     
   * CDN

* App Protection

   * Firewall (Static Public IP)
   
      When using FW, fixed Public IP is required.

     ![fw](https://raw.githubusercontent.com/QueenieCplusplus/QuickGoThru/master/FW.png)

   * DDoS Protection

     ![ddos](https://raw.githubusercontent.com/QueenieCplusplus/QuickGoThru/master/ddos%20protection.png)

   * Private Link

     ![private link](https://raw.githubusercontent.com/QueenieCplusplus/QuickGoThru/master/private%20link.png)

   * Spoke Network

