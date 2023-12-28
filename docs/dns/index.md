# DNS

O DNS, ou Domain Name System (Sistema de Nomes de Domínio), é um componente fundamental da Internet, funcionando como um diretório que permite a tradução de nomes de domínio amigáveis (como 'www.example.com') em endereços IP numéricos (como '192.0.2.1'), que são utilizados pelos computadores para identificar e se comunicar entre si na rede.

## Principais Características do DNS
1-`Tradução de Nomes para Endereços IP:` O DNS resolve nomes de domínio para os correspondentes endereços IP, permitindo que os usuários acessem websites e serviços online usando nomes fáceis de lembrar, em vez de endereços IP complexos.

2-`Funcionamento Hierárquico:` O sistema DNS é estruturado de forma hierárquica, com diferentes níveis de servidores DNS (servidores raiz, servidores de nível superior, servidores de domínio de segundo nível, etc.) que trabalham juntos para resolver consultas de nomes de domínio.

3-`Servidores DNS:` Existem servidores DNS distribuídos globalmente, que armazenam registros DNS contendo informações sobre domínios, como seus endereços IP associados (registros A ou AAAA), servidores de e-mail (registros MX), e outros.

4-`Cache DNS:`` Os resultados das consultas DNS são frequentemente armazenados em cache por servidores e clientes para melhorar a eficiência e reduzir a carga nos servidores DNS.

## Instalação

# No Windows (Configurando DNS no Cliente)
1 `Abrir Configurações de Rede:` 
Ir para Painel de Controle > Rede e Internet > Central de Rede e Compartilhamento > Alterar as configurações do adaptador.

2 `Propriedades do Adaptador:`
Clicar com o botão direito no adaptador de rede ativo e selecionar "Propriedades".

3 `Propriedades do Protocolo TCP/IP:`
Selecionar "Protocolo TCP/IP Versão 4 (TCP/IPv4)" ou "Protocolo TCP/IP Versão 6 (TCP/IPv6)" e clicar em "Propriedades".

4 `Definir DNS:`
Escolher "Usar os seguintes endereços de servidor DNS" e inserir o endereço DNS desejado.


## Configuração

Incluir o(s) nome(s) e o conteúdo do(s) arquivo(s) de configuração.

Cinco registros (4 pontos cada):

- 3 do tipo A (Endereços);
- 2 do tipo CNAME (`www` e `docs`);

## Teste
![dns](https://i.ibb.co/6W6753n/Screenshot-2023-12-26-19-19-35.png)

