

 🚀 Laboratório: Implementação de VPN IPsec sobre MPLS com Roteamento Dinâmico e Alta Disponibilidade 

 📌 Descrição do Laboratório

Este laboratório simula uma infraestrutura de rede corporativa combinando VPN IPsec e MPLS para fornecer segurança, escalabilidade e alta disponibilidade. O ambiente foi projetado para conectar filiais (SPOKEs) a uma matriz (HUB) através de túneis IPsec seguros, enquanto o tráfego entre os sites é roteado por um backbone MPLS VPN.  

 🎯 Objetivos

- Estabelecer VPNs IPsec com IKEv2 para garantir comunicação segura entre HUB e SPOKEs.  
- Configurar uma rede MPLS com suporte a VRFs para isolamento de tráfego corporativo.  
- Implementar roteamento dinâmico utilizando EIGRP para IPsec e OSPFv3 para MPLS.  
- Garantir alta disponibilidade com múltiplos túneis e caminhos redundantes.  

 🛠️ Componentes Configurados 

 🔹 HUB e SPOKEs
- Configuração de túneis IPsec (Tunnel100 e Tunnel200).  
- Implementação de IKEv2 e IPsec para autenticação e criptografia.  
- EIGRP para roteamento dinâmico sobre os túneis.  

 🔹 Backbone MPLS (PEs e Ps)
- MPLS e LDP para transporte eficiente de pacotes com labels.  
- OSPFv3 para roteamento dinâmico dentro da rede MPLS.  
- VRF (Virtual Routing and Forwarding)** para isolamento de tráfego do cliente "CLIENTE".  
- BGP para distribuição de rotas VPN entre os PEs.  

🔹 Outras Configurações Importantes 
- Loopbacks para identificação dos roteadores no MPLS e OSPFv3.  
- Redundância e alta disponibilidade por meio de múltiplos túneis e caminhos alternativos.  

 ✅ Benefícios para Infraestruturas Corporativas 

- Maior segurança com criptografia IPsec e isolamento MPLS VPN.  
- Escalabilidade e eficiência no roteamento dinâmico e suporte a múltiplos clientes.  
- Alta disponibilidade com caminhos redundantes para evitar falhas.  

📂 Todos os arquivos de configuração e prints das saídas dos comandos aplicados estão disponíveis neste repositório.  

🚀 Siga para mais laboratórios de redes e segurança!

#Networking #CCNP #MPLS #IPsec #VPN #EIGRP #OSPF #BGP #Cisco #CyberSecurity #InfraestruturaDeRedes
