# 💅 Nail Studio Pro

Sistema completo de agendamentos de manicure — web app (HTML/CSS/JS puro, offline, sem framework).

**App online:** https://tomm129.github.io/nail-studio-pro/

## Funcionalidades
- 📅 Agendamento com cliente, data, horário e tipo de serviço
- 📋 Lista de agendamentos agrupada por dia
- 🗓️ Grade semanal (horário × dia) com datas comemorativas destacadas
- ⏰ Visualização de horários livres por data
- 👥 Cadastro de clientes com botão direto pro WhatsApp
- ⚙️ Configuração de duração, valor e custo de cada serviço
- 💰 Caixa: faturamento, custo e lucro mensal (realizado × previsto)
- 💾 Dados salvos no próprio aparelho (localStorage)

## Instalar como app
- **Android / iPhone:** abra o link acima no navegador (Chrome/Safari) e use "Adicionar à tela de início".
- **Android (APK):** o app também é empacotado com Capacitor. Para gerar o APK:
  ```
  npx cap add android
  npx cap copy android
  cd android && ./gradlew assembleDebug
  ```

## Estrutura
- `index.html` — o app inteiro (interface + lógica)
- `manifest.json`, `sw.js`, `icon-*.png` — arquivos de PWA (ícone, instalação, funcionamento offline)
