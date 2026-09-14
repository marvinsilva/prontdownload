# 📋 Baixador de Prontuários Inconvenientes

Uma ferramenta web simples e eficiente para auxiliar residentes na extração e consolidação de relatórios hospitalares (AGHU) para fins de **estudo de caso e uso acadêmico**.

---

### ⚠️ Requisitos Importantes

* **Ambiente de Uso:** Esta ferramenta funciona **apenas em máquinas completas** (aquelas que exigem login de usuário no sistema operacional). Não funciona em terminais leves/simplificados.
* **Privacidade & Sigilo:** Ferramenta desenvolvida para uso interno e acadêmico. Mantenha sempre o sigilo dos dados dos pacientes e compartilhe apenas com pessoas de confiança da equipe.

---

### 🚀 Como Usar

#### Passo 1: Extrair as Páginas do Prontuário
1. Abra a aplicação web `index.html`.
2. **Opção A (Recomendada):** Arraste o botão lilás `🚀 Opção A` para a sua **Barra de Favoritos** do navegador (`Ctrl + Shift + B`).
3. **Opção B (Alternativa):** Clique em `📋 Opção B` para copiar o código extrator.
4. Vá para a aba do prontuário no sistema hospitalar (AGHU).
5. Execute a extração:
   * Se usou a **Opção A**: Clique no favorito salvo na sua barra.
   * Se usou a **Opção B**: Clique na barra de endereço do navegador, digite `javascript:`, cole o código copiado em seguida e aperte **Enter**.
6. Aguarde a rolagem automática e o download de todas as páginas em imagem (`.png`).

> 💡 **Nota:** Ao baixar muitas páginas pela primeira vez, certifique-se de clicar em **"Permitir"** caso o navegador pergunte se deseja autorizar o download de múltiplos arquivos.

---

#### Passo 2: Gerar o PDF Único
1. Volte para a página do **Baixador de Prontuários**.
2. Arraste todas as imagens baixadas para a área de soltar arquivos (ou clique para selecionar).
3. Clique em **"Converter e Baixar PDF Único"**.
4. O arquivo final `Prontuario_Completo.pdf` será gerado automaticamente com as páginas ordenadas.

---

### 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3** (Interface em Dark Mode)
* **JavaScript Vanilla** (Script Bookmarklet de automação DOM/iFrames)
* **[pdf-lib](https://pdf-lib.js.org/)** (Geração e unificação de PDFs no cliente)

---

### 👤 Autor

Desenvolvido por **Fg0kr1t1c0**
