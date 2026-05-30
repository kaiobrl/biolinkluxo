# Carlos imoves | Bio Link de Luxo

## 📋 Visão Geral

**Bio Link Digital Premium** para Carlos imoves - Corretor de Imóveis de Luxo. Uma plataforma elegante e sofisticada que funciona como um cartão de visita digital corporativo com integração de CRM para gestão de leads de alto padrão.

---

## 👤 Informações do Profissional

| Campo | Informação |
|-------|-----------|
| **Nome** | Carlos imoves |
| **Profissão** | Corretor de Imóveis de Luxo |
| **Especialidade** | Alto Padrão / Propriedades Premium |
| **CRECI** | 124.580-F |
| **Slogan** | "Transformando sonhos em endereços exclusivos com curadoria private de alto padrão." |
| **Status** | Online |

---

## 📱 Canais de Atendimento

### Contatos Principais
- **WhatsApp**: [+55 11 99824-3737](https://api.whatsapp.com/send?phone=5583981374944)
- **E-mail**: [formatolivre1.com.br](mailto:formatolivre1@gmail.com)
- **Website**: [formatolivre1.com.br](https://alancarluxury.com.br)
- **Localização**: Geisel, Joao Pessoa - PB
- **Endereço**: Av. juscelino kubitschek, 4500 - Geisel, Joao Pessoa - PB

### Redes Sociais
- **Instagram**: [@formato_livre](https://instagram.com/formato_livre)
- **LinkedIn**: [linkedin.com/in/kaiobrl](https://linkedin.com/in/kaiobrl)
- **Facebook**: [facebook.com/robertoalencar.lux](https://facebook.com/kaiobrl)

---

## 🏢 Oportunidade em Destaque: Aura Penthouse

### Informações Principais
| Atributo | Descrição |
|----------|-----------|
| **Nome** | juscelino kubitschek • Geisel |
| **Tipo** | Penthouse |
| **Localização** | Geisel, Joao Pessoa - PB |
| **Valor** | R$ 18.500.000 |
| **Área Total** | 640 m² |
| **Suítes** | 4 Master |
| **Banhos** | 6 banheiros |
| **Vagas** | 5 garagens |

### Descrição Premium
Uma impressionante cobertura residencial duplex de grife internacional com arquitetura moderna de contornos minimalistas e vanguarda. O imóvel dispõe de adega gourmet privativa climatizada para 120 garrafas, spa com piscina privativa suspensa com borda infinita totalmente integrada ao living social e com vista 360° definitiva para o skyline verde dos Jardins.

### Diferenciais Oferecidos
- ✅ Borda Infinita Suspensa
- ✅ Adega Climatizada (120 garrafas)
- ✅ Automação Control 4 (Casa Inteligente)
- ✅ Elevador Privativo Codificado
- ✅ Entrada Facial Ativa
- ✅ Piscina Privativa Suspensa
- ✅ Spa e Wellness Area
- ✅ Vista 360° Skyline

---

## 🎨 Design & Tecnologia

### Paleta de Cores Corporativa
```
Cor Primária (Ouro Luxuoso):  #D4AF37
Cor Secundária (Ouro Claro):  #F3E5AB
Cor Terciária (Ouro Escuro):  #AA7C11
Fundo Escuro:                 #0F0F0F, #1A1A1A, #050505
```

### Dependências Visuais
- **Google Fonts**: Montserrat (pesos 100-900)
- **FontAwesome**: v6.4.0 (Ícones Premium)
- **Tailwind CSS**: v4 Browser Engine
- **Efeito Visual**: Glassmorphism com Backdrop Filter

### Padrão Geométrico
Fundo arquitetônico de alta fidelidade com gradientes angulares (30°, 60°, 150°) criando padrão geométrico sofisticado.

### Componentes de Interface
- **Barra de Rolagem Customizada**: Espessura 6px com acentos dourados (opacidade 0.25-0.5)
- **Cards Glassmorphism**: Blur 25px, fundo translúcido 8% branco, borda 18% branca
- **Animações**:
  - Fade In Slide (0.75s)
  - Soft Ping (2.5s infinita)
  - Hover Effects em ícones e botões

---

## 🔧 Estrutura Funcional

### 1. **Visualização Cliente** (Client View)
Cartão de visita digital elegante com:
- Perfil do corretor com foto circular
- Indicador de status "Online"
- Grade 2x2 de canais de atendimento rápido
- Botão principal "Salvar na Agenda" (vCard)
- Card destacado da oportunidade do mês

### 2. **Painel Broker** (Broker Dashboard)
CRM integrado com funcionalidades:
- Métricas rápidas (Total de Leads, Fechamentos, Comissões Estimadas)
- Tabela dinâmica de leads ativos
- Comutador de status de leads (Novo, Em Atendimento, Visita Agendada, Negócio Fechado)
- Ações: Exportação CSV, Limpeza de Base

### 3. **Modal de Detalhes de Imóvel**
Apresentação completa da propriedade com:
- Imagem em alta resolução
- Grid de atributos (4 colunas)
- Memorial descritivo
- Diferenciais com checkmarks
- Formulário de captura de leads
- Painel de sucesso com redirecionamento WhatsApp

### 4. **Modal de Compartilhamento**
- Simulação visual de QR Code (SVG interativa)
- Campo de cópia rápida de link
- Moldura dourada (#D4AF37)

---

## 💾 Sistema de Leads & CRM

### Armazenamento Local
- **LocalStorage Key 1**: `luxury_leads` → Array JSON com dados dos leads
- **LocalStorage Key 2**: `luxury_leads_statuses` → Object com status individual de cada lead
- **LocalStorage Key 3**: `luxury_clicks` → Contador simples de interações (142 padrão)

### Estrutura de Lead Capturado
```javascript
{
  id: 'lead_1780150338119',
  name: 'Nome Completo',
  phone: '(11) 99999-9999',
  email: 'email@corporate.com',
  budget: 'R$ 5M - R$ 10M',
  message: 'Mensagem particular do cliente',
  propertyTitle: 'juscelino kubitschek • Geisel',
  timestamp: '30/05/2026 14:30:45'
}
```

### Fluxo de Captura
1. Usuário clica "VER DETALHES" no card do imóvel
2. Modal se abre com formulário de 4 campos obrigatórios
3. Usuário preenche: Nome, Telefone, E-mail e Budget (opcional: Mensagem)
4. Ao submeter, lead é armazenado em LocalStorage
5. Painel de sucesso aparece com animação
6. Redirecionamento automático para WhatsApp com mensagem pré-formatada

### Campos de Formulário
| Campo | Tipo | Obrigatório | Placeholder |
|-------|------|-----------|-----------|
| Nome Completo | Text | ✅ | Ex: Dr. Roberto Mendes |
| Telefone/WhatsApp | Tel | ✅ | Ex: (11) 99999-9999 |
| E-mail Corporativo | Email | ✅ | Ex: r.mendes@private.com |
| Previsão de Ticket | Select | ❌ | R$ 3M-5M, 5M-10M, >10M |
| Mensagem Particular | Textarea | ❌ | Campo livre |

### Gestão de Status de Leads
Comutador dropdown com 4 estados:
- 🔵 **Novo** (Azul) - Estado padrão
- 🟠 **Em Atendimento** (Âmbar) - Contato iniciado
- 🟣 **Visita Agendada** (Índigo) - Visitação confirmada
- 🟢 **Negócio Fechado** (Esmeralda) - Transação concluída

### Cálculo de Comissões
- Comissão simulada por venda: **R$ 180.000,00**
- Total = Número de negócios fechados × R$ 180.000

### Exportação de Dados
Formato CSV com campos:
- ID, Nome, E-mail, Telefone, Ticket Médio, Mensagem, Imóvel de Interesse, Data/Hora, Status
- Nome do arquivo: `Clientes_Especiais_Carlos_imoves_YYYY-MM-DD.csv`

---

## ⚙️ Funcionalidades JavaScript (Vanilla)

### Funções Principais

| Função | Propósito |
|--------|----------|
| `loadLeads()` | Carrega leads do localStorage |
| `saveLeads()` | Persiste leads no navegador |
| `logClick(actionType)` | Rastreia cliques e interações |
| `generatevCard()` | Gera arquivo .vcf para salvar contato |
| `openPropertyModal()` | Abre modal de detalhes |
| `closePropertyModal()` | Fecha modal de detalhes |
| `openQRModal()` | Abre modal de compartilhamento |
| `closeQRModal()` | Fecha modal de compartilhamento |
| `handleLeadRegistration(event)` | Processa submissão de formulário |
| `toggleViewMode()` | Alterna entre Client View e Broker Panel |
| `updateDashboardView()` | Atualiza métricas e tabela CRM |
| `updateLeadStatus(leadId, value)` | Altera status individual do lead |
| `clearCapturedLeads()` | Limpa todos os dados locais |
| `exportDatabaseToCSV()` | Exporta dados em CSV |
| `copyShareLink()` | Copia link para clipboard |

### Rastreamento de Eventos
- `whatsapp` - Clique no botão WhatsApp
- `location` - Clique no mapa/escritório
- `email` - Clique no e-mail
- `website` - Clique no portfolio
- `instagram` - Clique no Instagram
- `linkedin` - Clique no LinkedIn
- `facebook` - Clique no Facebook
- `vcard_download` - Download do vCard
- `prop_detail_load` - Abertura de detalhes
- `qr_share_load` - Abertura de compartilhamento
- `view_mode_client` / `view_mode_broker` - Alternância de visualização

### Redirecionamento WhatsApp Automático
Mensagem pré-formatada enviada com:
- Nome do cliente
- Título da propriedade
- Localização
- Dados de contato do cliente
- Mensagem particular do cliente

---

## 📲 Arquivos & Estrutura

```
Roberto Alencar Bio Link de Luxo/
├── index.html          (Arquivo principal - HTML5)
├── index.md           (Este documento - Documentação)
├── index.js           (Lógica JavaScript adicional - referenciado)
├── index.css          (Estilos adicionais - referenciado)
└── /src/
    └── /assets/
        └── /images/
            ├── broker_profile_1780150338119.png
            ├── modern_estate_1780150353703.png
            └── luxury_mansion_1780150323966.png
```

---

## 🎯 Fluxo de Usuário

### Para Visitantes (Cliente)
1. Acessa o link do bio
2. Visualiza cartão completo do corretor
3. Explora canais de contato (WhatsApp, E-mail, etc)
4. Clica em "VER DETALHES" para saber mais sobre a propriedade
5. Preenche formulário de interesse
6. Redirecionado para WhatsApp automático

### Para Broker (Painel Administrativo)
1. Clica no botão "PAINEL BROKER" no topo esquerdo
2. Visualiza métricas de desempenho
3. Gerencia leads na tabela interativa
4. Altera status de cada lead
5. Exporta base de dados em CSV
6. Pode contatar leads via WhatsApp direto

---

## 🔒 Recursos de Segurança

- Validação de campos obrigatórios no formulário
- Sanitização de caracteres especiais em CSV (aspas duplicadas)
- Codificação de URL para WhatsApp
- Bloco de confirmação antes de limpar dados
- LocalStorage isolado por domínio (navegador)

---

## 📊 Dimensões & Responsividade

- **Desktop**: Max-width 1024px
- **Mobile**: Max-width 768px com restrição 448px
- **Viewport**: Meta viewport configurada (width=device-width, initial-scale=1.0)
- **Overflow**: Tratamento de rolagem com height máximos

---

## 🌐 Compatibilidade

- ✅ Chrome/Chromium 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Mobile Safari (iOS 14+)
- ✅ Samsung Internet 14+

---

## 📝 Marcas & Propriedade Intelectual

- **Empresa**: Carlos imoves Estates
- **Slogan**: LUXURY EXCLUSIVITY CERTIFIED
- **Ano Atual**: Dinâmico (inserido por JavaScript)
- **Copyright**: © 2026 imoves Luxurious Estates

---

## 🚀 Recursos Técnicos Avançados

- **CSS Customizado**: Variáveis CSS para cores corporativas
- **Responsividade**: Grid adaptável (2 colunas desktop, 1 mobile)
- **Performance**: Lazy loading de imagens com fallback Unsplash
- **Acessibilidade**: Atributos `title`, `aria-label` onde aplicável
- **SEO**: Meta tags, estrutura semântica HTML5
- **Microinterações**: Animações suaves em hover/click

---

## 📞 Como Utilizar

### 1. Compartilhar o Bio Link
- Copie o link via botão QR
- Distribua para clientes potenciais
- Redes sociais, e-mail, WhatsApp

### 2. Acompanhar Leads
- Acesse o PAINEL BROKER
- Visualize todas as solicitações
- Altere status conforme o progresso
- Exporte lista em CSV para CRM externo

### 3. Atualizar Informações
Editar `index.html` diretamente para:
- Telefone/WhatsApp
- E-mails corporativos
- Localização
- Propriedades em destaque
- Dados do imóvel (preço, área, etc)

---

## 📅 Última Atualização

**Data**: 30 de Maio de 2026  
**Status**: Ativo e Funcional  
**Versão**: 1.0 Premium

---

## 📚 Documentação Técnica Resumida

- **Linguagem Principal**: HTML5 + CSS3 + JavaScript Vanilla
- **Framework CSS**: Tailwind CSS v4 (CDN)
- **Fonte**: Google Fonts Montserrat
- **Ícones**: FontAwesome 6.4.0
- **Storage**: LocalStorage API
- **APIs Externas**: WhatsApp Business API, Google Maps API (Waze)

---

**Desenvolvido com excelência para proporcionar experiência premium em vendas de imóveis de luxo.**
