# 🔍 Lupa Falante

**Lupa Falante** é uma aplicação Android profissional e altamente acessível, desenhada especificamente para auxiliar pessoas com deficiência visual e dificuldades motoras ou de visão. Ao combinar uma lupa digital de alta performance com Reconhecimento Ótico de Carateres (OCR) em tempo real e Síntese de Voz (Text-to-Speech), a Lupa Falante transforma qualquer smartphone Android numa ferramenta de apoio indispensável.

---

## ✨ Funcionalidades Principais

- **📷 Lupa de Alta Performance (CameraX)**: Pré-visualização da câmara em direto com controlos rápidos de zoom (`+` / `-` e indicador visual).
- **🗣️ Leitor de Texto em Voz Alta (OCR + TTS)**: Alimentado pelo Google ML Kit e pelo sistema de voz do Android, captura texto visível (rótulos, documentos, cartazes) e lê-o em voz alta em Português.
- **❄️ Congelamento de Imagem (Snapshot)**: Permite pausar a câmara numa fotografia estática para examinar pequenos detalhes ou ler texto sem tremores nas mãos.
- **🎨 Filtros de Acessibilidade Avançados**:
  - **Normal**: Cores originais.
  - **Preto e Branco (Grayscale)**: Escala de cinzentos pura de alto contraste.
  - **Cores Invertidas (Negativo)**: Fundo escuro com texto claro, eliminando o brilho e o cansaço visual.
  - **Alto Contraste**: Amplifica as diferenças tonais para máxima legibilidade.
- **🔦 Controlo de Lanterna (Flash)**: Luz integrada para leitura em ambientes escuros.
- **🔊 Feedback de Voz Áudio**: Cada toque em botões e mudança de estado é anunciado verbalmente, garantindo total acessibilidade para utilizadores com deficiência visual severa.
- **💶 Botões de Apoio e Sugestões**: Atalhos no topo central para doações (PayPal) e envio de feedback (Google Forms).

---

## 🛠️ Tecnologias Utilizadas

- **Interface (UI)**: Jetpack Compose & Material 3 (Tema escuro de alto contraste otimizado para baixa visão).
- **Câmara**: Android CameraX (`camera-core`, `camera-camera2`, `camera-lifecycle`, `camera-view`).
- **Reconhecimento de Texto**: Google ML Kit (`com.google.mlkit:text-recognition`).
- **Síntese de Voz**: Android `TextToSpeech`.
- **Arquitetura**: Kotlin Coroutines e gestão de estado reativa.

---

## 📱 Instalação e Utilização

1. **Permissão de Câmara**: Ao abrir a aplicação pela primeira vez, autorize o acesso à câmara para iniciar a lupa.
2. **Ajustar Zoom**: Utilize os botões `+` e `-` do lado direito para ampliar o texto.
3. **Congelar Imagem**: Pressione **Congelar** para fixar a imagem atual e examiná-la confortavelmente.
4. **Ler em Voz Alta**: Pressione **Ler Texto** para extrair o texto da câmara ou da imagem congelada e ouvi-lo sintetizado em voz alta.
5. **Mudar Filtros**: Toque no botão **Filtro** no topo para alternar entre os vários modos visuais de alto contraste.
