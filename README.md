# Fuga da Masmorra

### Como Jogar
Nos arquivos do jogo logo acima, há um PDF com um tutorial ilustrado caso queria seguir um passo a passo visualmente, é só clicar nele e seguir os passos.

---

Jogar Localmente (no seu computador)

Para rodar o jogo offline sem lentidão, você precisa usar um servidor local. Não se preocupe, é um processo simples de um comando.

**Pré-requisito:**
* Você precisa ter um navegador web instalado no seu computador.
* Você precisa ter o **Python** instalado no seu computador.

---

**Instruções:**
1.  Baixe o repositório completo clicando em **Code** e depois em **Download ZIP**.
2.  Descompacte o arquivo ZIP em uma pasta.
3.  Abra um terminal (Prompt de Comando ou PowerShell no Windows, ou Terminal no Mac/Linux) dentro da pasta do jogo.
    Uma forma rápida de fazer isso no Windows é segurando a tecla **Shift** e clicando com o botão direito do mouse dentro da pasta, escolhendo a opção "Abrir janela do PowerShell aqui".
4.  No terminal, digite o seguinte comando e pressione **Enter**:

     Linux / Mac:
        ```bash
        python -m http.server
        ```

    Windows: ```python -m http.server```

5.  Abra seu navegador e acesse o endereço `http://localhost:8000`. O jogo será carregado e deverá rodar normalmente.

---

### Sobre o Projeto

Este jogo foi desenvolvido usando o **Construct 3**, uma ferramenta para criação de jogos em HTML5. O objetivo foi criar uma experiência divertida e desafiadora, com diferentes fases e mecânicas.

---

### Créditos

* **Desenvolvimento:** ONEmerson
* **Ferramenta de Desenvolvimento:** Construct 3

---

### Licença

Este projeto está licenciado sob a Licença [Creative Commons Atribuição-NãoComercial-SemDerivações 4.0 Internacional](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.pt).

---

### Regras
Movimento: esquerda/direita, pulo, queda controlada e subida em plataformas.

---

### Combate:

Marreta elimina os Porcos Patrulheiros e quebra caixas.

O golpe no projétil de canhão devolve-o ao Porco Atirador, derrotando-o.

Bomba (obtida no baú) é necessária para derrotar o Porco Rei.

---

### Interação com Objetos:

Chave obtida ao derrotar Porco Atirador abre o baú.

Baú contém bomba para enfrentar Porco Rei.

---

### Elementos Narrativos:

Morcego aparece em áreas internas como guia para caminhos e segredos.

Morcego não aparece em ambientes externos iluminados.

---

### Condições de Derrota:

Contato com inimigos causa dano.

Porco Patrulheiro dano parcial.

Porco Atirador dano parcial.

Porco Rei, Dano total, Fatal Hit.

O morcego não é um inimigo apesar de parecer.

Cair fora da área jogável reinicia a fase.

Cair na água reinicia a fase.

Cair fora do cenário reinicia a fase.

Perder toda a vida reinicia a fase.

Ao sobrar zero corações cheios no Hud, qualquer dano reinicia a fase.

---

### Entradas para realizar as ações:


Andar: 
Para a esquerda
    Botão do teclado “A”
Para a direita
    Botão do teclado “D”


Pular: 
    Uma ou Duas vezes
    Botão do teclado “W”


Coletar item:
    Tocar na Chave (Caso matar o porco atirador)
    Tocar na Bomba (Caso abrir o baú de item)


Atacar: 
    Com a marreta:
    Botão do teclado “Espaço”

Com bomba: (caso tiver coletado o item)
    Botão do teclado “S”
