<p align="center">
  <img width="160" alt="Perdemo" src="https://github.com/user-attachments/assets/c936e520-249e-47b3-9d78-c691d8958e27" />
</p>

<h1 align="center">Perdemo</h1>

<p align="center">
  Perdemo é um app de voz, chat e transmissão de tela para jogar com amigos. Crie salas, brinque com seus amigos, descubra todos os segredos do app e personalize o perfil com GIFs. Conecte-se pela rede local, VPN ou internet, sem servidor central. E se alguém exagerar, a sala vota e manda seu amigo para o espaço!
</p>

<p align="center">
  <a href="https://github.com/JhowUno/Perdemo/releases"><b>⬇ Baixar o Perdemo</b></a>
</p>

---

## O que dá para fazer

🎙️ **Salas de voz**: crie uma sala, chame a galera e converse enquanto joga. Dá para colocar senha na sala.

💬 **Chat**: mande mensagens, GIFs, imagens e arquivos, responda mensagens de alguém e receba aviso quando responderem você.

🖥️ **Transmissão de tela**: mostre o seu jogo para os amigos da sala e assista o que eles estão jogando.

🎨 **Perfil do seu jeito**: escolha um GIF ou uma imagem, mude a cor do seu nome e adicione efeitos como brilho e sombra.

🌍 **Planeta ao vivo**: veja no globo onde seus amigos estão conectados.

☢️ **Nuke e votação**: alguém passou dos limites? A sala vota e o míssil faz o resto. 🚀

🕵️ **Segredos**: o Perdemo esconde algumas surpresas. Boa sorte para encontrar todas!

<p align="center">
  <img width="1320" height="800" alt="pingA" src="https://github.com/user-attachments/assets/41448de3-4660-418d-be49-b1309eaa03d1" />
</p>

## Como começar

1. Baixe o `Perdemo.exe` na página de [versões](https://github.com/JhowUno/Perdemo/releases).
2. Abra o arquivo. Não precisa instalar nada.
3. Escolha seu nome e sua foto.
4. Crie uma sala ou entre na sala de um amigo.

> Se o Windows perguntar sobre o firewall, permita o acesso. Assim os seus amigos conseguem te encontrar. Também dá para fazer isso depois em **Configurações → Geral → Configurar firewall**.

## Jogando com amigos de longe

O Perdemo encontra sozinho quem está na mesma rede que você. Para jogar com amigos de outras casas, vocês podem usar uma VPN de jogos, como **Radmin VPN** ou **Hamachi**, e entrar na mesma rede. Depois é só abrir o Perdemo.

Em **Configurações → Geral** você escolhe como se conectar:
- **Rede Global**: tenta conectar a voz direto pela internet.
- **Rede local e VPN**: encontra amigos na sua rede e nas redes VPN.

## Atualizações

O Perdemo avisa quando sai uma versão nova e se atualiza sozinho.

## Requisitos

- Windows 10 ou 11 (64 bits)
- Microfone e fone de ouvido (recomendado)

## Solução de problemas

<p align="center">
  Erro: O controle inteligente de aplicativos bloqueou um aplicativo que pode não ser seguro
  <img width="500" alt="Gemini_Generated_Image_aoqctraoqctraoqc" src="https://github.com/user-attachments/assets/264f9a74-47db-4e6a-81f5-cf0374fb86e3" />
</p>

Você precisa desativar temporariamente ou permanentemente o Controle Inteligente de Aplicativos (Smart App Control) nas configurações do sistema.
1. Clique no Menu Iniciar do Windows.
2. Digite Segurança do Windows e abra o aplicativo.
3. No menu lateral esquerdo, clique em Controle de aplicativos e do navegador.
4. Procure e clique em Configurações do controle inteligente de aplicativos.
5. Marque a opção Desativado.
6. Feche a janela e tente abrir ou instalar o aplicativo novamente (se necessário, reinicie o computador)

<p align="center">
  Se a opção desativar estiver indisponível, apresentando a mensagem: "Essa configuração é gerenciada pelo controle inteligente de aplicativos"
  <img width="500" alt="Gemini_Generated_Image_3wcgon3wcgon3wcg" src="https://github.com/user-attachments/assets/566b90f6-8895-4b22-9db5-aef89958fb42" />
</p>

É necessário desativar através do Registro do Windows:
1. No seu teclado, pressione as teclas Windows + R para abrir a caixa "Executar".
2. Digite regedit e pressione Enter (clique em "Sim" se o Windows pedir permissão de administrador).
3. Na barra de endereços do topo do Editor do Registro, copie, cole o seguinte caminho e aperte Enter: HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\CI\Policy
4. No lado direito da janela, procure por um valor chamado VerifiedAndReputablePolicyState.
5. Dê dois cliques rápidos em cima dele.
6. No campo "Dados do valor", mude o número atual para 0 (zero) e certifique-se de que a base está em Hexadecimal.
7. Clique em OK.
8. Reinicie o seu computador para que a alteração tenha efeito.
Após reiniciar, o Controle Inteligente de Aplicativos estará completamente desligado, permitindo que você abra o programa bloqueado.

## Feito por

**JhowUno**, **Rick_Silvac** e **ClaudeAI**.
