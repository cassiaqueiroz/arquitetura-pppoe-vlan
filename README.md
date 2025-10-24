# Arquitetura PPPoE/VLAN - Documentação Interativa

## 📋 Descrição

Documentação técnica interativa que demonstra o fluxo completo de autenticação PPPoE com segmentação VLAN em redes de telecomunicações. O projeto apresenta de forma visual e educativa como funciona a jornada desde o login/senha do cliente até o estabelecimento da conexão com a internet.

## 🚀 Funcionalidades

- **Diagrama Interativo**: Visualização passo a passo do processo de autenticação
- **Animações Controladas**: Sistema de play/pause/reset para acompanhar o fluxo
- **Resumo Visual**: Visão panorâmica com zonas de responsabilidade
- **Glossário Técnico**: Definições detalhadas dos componentes (OLT, PON, VLAN, RADIUS, ISP, PPPoE, GPON)
- **Design Responsivo**: Compatível com desktop, tablet e mobile
- **Tooltips Informativos**: Explicações contextuais ao passar o mouse
- **Atalhos de Teclado**: Navegação rápida (Espaço, R, I)

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização moderna com gradientes, animações e flexbox/grid
- **JavaScript**: Interatividade e controles de animação
- **Font Awesome**: Ícones vetoriais
- **Google Fonts**: Tipografia (Inter e JetBrains Mono)

## 📁 Estrutura do Projeto

```
arquitetura-linca/
├── index.htm          # Página principal
├── styles.css         # Estilos CSS
└── README.md          # Documentação
```

## 🎯 Componentes Explicados

### Fluxo PPPoE/VLAN

1. **Roteador Cliente**: Inicia PPPoE Discovery (PADI)
2. **Tagging VLAN**: Tráfego recebe VLAN ID (802.1Q)
3. **OLT/PON**: Processamento em rede GPON
4. **BRAS/BNG**: Servidor PPPoE desencapsula e processa
5. **RADIUS**: Autenticação AAA centralizada
6. **Conexão Estabelecida**: Access-Accept e acesso à internet

### Glossário Técnico

- **OLT**: Optical Line Terminal - Gerencia múltiplas ONUs
- **PON**: Passive Optical Network - Rede de fibra passiva
- **VLAN**: Virtual LAN - Segmentação lógica 802.1Q
- **RADIUS**: Remote Authentication Dial-In User Service
- **ISP**: Internet Service Provider
- **PPPoE**: Point-to-Point Protocol over Ethernet
- **GPON**: Gigabit Passive Optical Network

## 🎨 Características do Design

- **Paleta Clean**: Tons frios e profissionais
- **Animações Suaves**: Transições e efeitos de entrada
- **Cards Interativos**: Hover effects e feedback visual
- **Layout Adaptativo**: Grid responsivo para todos os dispositivos
- **Acessibilidade**: Focus states e suporte a motion reduction

## 📱 Responsividade

O projeto foi desenvolvido com abordagem mobile-first:
- **Desktop**: Layout completo com animações avançadas
- **Tablet**: Adaptação de grid e reposicionamento de elementos
- **Mobile**: Layout em coluna única com navegação otimizada

## 🚀 Como Usar

1. Abra o arquivo `index.htm` em qualquer navegador moderno
2. Use os controles para navegar pela animação:
   - ▶️ Play: Inicia a animação sequencial
   - ⏸️ Pause: Pausa a animação
   - 🔄 Reset: Reinicia o diagrama
   - ℹ️ Info: Abre modal com informações técnicas
3. Explore os tooltips passando o mouse sobre cada etapa
4. Navegue pelas seções: Diagrama, Resumo Visual e Glossário

## 🎹 Atalhos de Teclado

- **Espaço/Enter**: Reproduzir animação
- **R**: Reiniciar diagrama
- **I**: Abrir informações técnicas

## 📊 Métricas do Sistema

- **Tempo de Autenticação**: 2-5 segundos
- **Etapas do Processo**: 6 principais
- **Tecnologia**: GPON
- **Segurança**: AAA (Authentication, Authorization, Accounting)

## 🎓 Fins Educacionais

Este projeto foi desenvolvido para fins educacionais, visando:
- Facilitar o entendimento de conceitos de redes
- Demonstrar fluxos de autenticação em ISPs
- Explicar tecnologias como GPON, PPPoE e VLAN
- Servir como material de apoio para estudos de telecomunicações

## 👨‍💻 Desenvolvedor

**cassiaqueirozcodelab** - Documentação técnica especializada para educação em redes e telecomunicações.

---

© 2025 Documentação desenvolvida por cassiaqueirozcodelab para fins educacionais