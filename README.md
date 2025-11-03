# Temporizador de Desligamento (turnoff.py)

## 💻 Descrição
Este é um aplicativo de desktop simples, construído com a biblioteca `tkinter` do Python, que permite ao usuário agendar ou cancelar o desligamento do sistema operacional (Windows) após um período de tempo definido.

O script utiliza o comando nativo do Windows `shutdown` para gerenciar o temporizador.

## ✨ Funcionalidades
*   **Interface Gráfica (GUI):** Fácil de usar, desenvolvida com `tkinter`.
*   **Agendamento Flexível:** Permite definir o tempo de desligamento em **Minutos** ou **Horas**.
*   **Ativação e Cancelamento:** Botões dedicados para iniciar o temporizador (`shutdown -s -t <segundos>`) e para cancelar qualquer agendamento pendente (`shutdown -a`).
*   **Feedback de Status:** Exibe mensagens de status e erros na interface.
*   **Créditos:** Inclui um link clicável para o GitHub do autor.

## ⚙️ Requisitos
Para executar este script, você precisará:
1.  **Python 3.x** instalado.
2.  **Sistema Operacional Windows** (o comando `shutdown` é específico para Windows neste contexto).
3.  As bibliotecas `tkinter`, `subprocess` e `webbrowser` (geralmente já inclusas na instalação padrão do Python).

## 🚀 Como Usar

1.  **Execute o script:**
    ```bash
    python turnoff.py
    ```

2.  **Defina o Tempo:**
    *   Insira o valor numérico no campo "Tempo".
    *   Selecione a unidade de tempo desejada: "Minutos" ou "Horas".

3.  **Ativar o Timer:**
    *   Clique no botão **"Ativar Timer"**.
    *   Uma mensagem de confirmação será exibida, e o status na parte inferior da janela será atualizado.

4.  **Desativar o Timer:**
    *   A qualquer momento, clique no botão **"Desativar Timer"** para cancelar o desligamento agendado.
    *   O aplicativo informará se o cancelamento foi bem-sucedido ou se não havia nenhum desligamento agendado.

## ⚠️ Observação
O script foi projetado para funcionar em **sistemas operacionais Windows** devido ao uso do comando `shutdown -s -t` e `shutdown -a`. Em sistemas Linux ou macOS, o comando de desligamento seria diferente.

## 📝 Créditos
Desenvolvido por Jonas Augusto. O link para o GitHub do autor está incluído na interface do aplicativo.
