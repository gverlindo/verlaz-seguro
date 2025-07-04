# 🛡️ Sistema de Seguro Internacional Verlaz

Sistema completo para cotação e contratação de seguro internacional, desenvolvido para a plataforma Verlaz. O sistema oferece validação de países e NCMs, integração com Frete Intelligence e gestão completa do processo de seguro.

## 🌐 **Demo Online**
**URL:** [https://xyvfvtyo.manus.space](https://ykigyqbu.manus.space/#)

## 📋 **Funcionalidades Principais**

### 🎯 **Três Fluxos Principais**
1. **Fazer Cotação via Verlaz** - Processo completo de cotação com validações
2. **Não Fazer Seguro** - Exibe vantagens do seguro para convencimento
3. **Já Contratei Seguro** - Coleta informações de seguro contratado externamente

### 🌍 **Validação de Países**
- **20 países restritos** validados automaticamente
- **Dropdown com filtro** por digitação
- **Pop-up educativo** para países com restrições
- **Lista baseada na AXA Seguros**

### 📦 **Validação de NCMs**
- **2.193 NCMs catalogadas** (amostra implementada)
- **Marcação com asterisco (*)** para NCMs que necessitam análise
- **Soma automática** dos valores das NCMs selecionadas
- **Alertas informativos** sobre restrições

### 🚚 **Frete Intelligence 1.0**
- **Modal completo** para cálculo de frete
- **Múltiplos países** e modalidades (Aéreo/Marítimo)
- **Importação automática** do valor calculado
- **Simulação realista** de consulta a agentes de carga

### 📊 **Status da Apólice**
- **Acompanhamento completo** do processo
- **Diferentes status**: Em andamento, Confirmada, Rejeitada
- **Extração de boleto** quando autorizado
- **Botão cancelar** para apólices não emitidas

## 🛡️ **Coberturas do Seguro**

| Cobertura | Percentual | Descrição |
|-----------|------------|-----------|
| **Valor da Mercadoria** | Até 100% | Proteção contra perda ou dano da carga |
| **Frete** | Até 100% | Reembolso proporcional ao valor da mercadoria avariada |
| **Despesas Operacionais** | Até 10% | Compensa custos extras com a importação |
| **Lucro Estimado** | Até 10% | Compensa o lucro que deixaria de ganhar |
| **Impostos na Importação** | 25% sobre valor + frete | Indenização pelos tributos pagos (com DI registrada) |

## 🔧 **Tecnologias Utilizadas**

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização responsiva
- **JavaScript Vanilla** - Funcionalidades interativas
- **JSON** - Dados de países e NCMs
- **CSV** - Base de dados de NCMs restritas

## 📁 **Estrutura do Projeto**

```
seguro-internacional-verlaz/
├── index.html              # Arquivo principal do sistema
├── paises-restritos.json   # Lista de países com restrições
├── ncms-restritas.csv      # Base de NCMs que necessitam análise
└── README.md              # Documentação do projeto
```

## 🚀 **Como Usar**

### **Instalação Local**
1. Clone o repositório
2. Abra o arquivo `index.html` em um navegador
3. O sistema funcionará completamente offline

### **Deploy**
- O sistema é 100% frontend
- Pode ser hospedado em qualquer servidor web
- Compatível com GitHub Pages, Netlify, Vercel, etc.

## 📱 **Funcionalidades Detalhadas**

### **Cotação de Seguro**
- ✅ Validação de país de origem
- ✅ Seleção de NCMs com valores
- ✅ Cálculo automático de totais
- ✅ Integração com Frete Intelligence
- ✅ Simulação de cotação com seguradoras

### **Frete Intelligence**
- ✅ Seleção de país e modalidade
- ✅ Campos condicionais para transporte aéreo
- ✅ Cálculo simulado de frete
- ✅ Importação automática do valor

### **Validações**
- ✅ Países restritos com pop-up informativo
- ✅ NCMs com asterisco para análise
- ✅ Campos obrigatórios
- ✅ Formatação automática de valores

## 🎨 **Interface**

### **Design Responsivo**
- ✅ Compatível com desktop e mobile
- ✅ Interface intuitiva e profissional
- ✅ Cores e tipografia consistentes
- ✅ Feedback visual para todas as ações

### **Experiência do Usuário**
- ✅ Navegação fluida entre seções
- ✅ Loading states para operações
- ✅ Mensagens de confirmação
- ✅ Alertas informativos

## 📊 **Dados e Validações**

### **Países Restritos (20 países)**
Baseado na lista oficial da AXA Seguros:
- Afeganistão, Belarus, China, Cuba, Irã, Rússia, Síria, Venezuela, etc.

### **NCMs Restritas (2.193 registros)**
- Base completa de NCMs que necessitam análise da seguradora
- Marcação visual com asterisco (*)
- Alertas informativos sobre o processo

## 🔄 **Fluxos do Sistema**

### **1. Cotação Completa**
```
Início → Dados do Cliente → País (Validação) → NCMs → Frete → Cotação → Contratação → Status
```

### **2. Não Fazer Seguro**
```
Início → Exibição de Vantagens → Retorno ao Dashboard
```

### **3. Já Contratei**
```
Início → Informar Valor → Retorno ao Dashboard
```

### **4. Status da Apólice**
```
Cliente Existente → Status Atual → Ações Disponíveis → Dashboard
```

## 🛠️ **Configurações**

### **Personalização**
- Valores de NCMs podem ser editados no HTML
- Lista de países pode ser expandida no JavaScript
- Cores e estilos podem ser modificados no CSS
- Textos e mensagens são facilmente editáveis

### **Integração**
- Pronto para integração com APIs reais
- Estrutura preparada para backend
- Dados organizados para fácil migração

## 📈 **Métricas e Analytics**

### **Funcionalidades Implementadas**
- ✅ 100% das validações funcionando
- ✅ Todos os fluxos testados
- ✅ Interface responsiva
- ✅ Compatibilidade cross-browser

### **Performance**
- ⚡ Carregamento instantâneo
- ⚡ Operações em tempo real
- ⚡ Sem dependências externas
- ⚡ Otimizado para mobile

## 🤝 **Contribuição**

### **Como Contribuir**
1. Fork o projeto
2. Crie uma branch para sua feature
3. Commit suas mudanças
4. Push para a branch
5. Abra um Pull Request

### **Padrões de Código**
- HTML semântico e acessível
- CSS organizado e comentado
- JavaScript limpo e documentado
- Commits descritivos

## 📞 **Suporte**

### **Contato**
- **Projeto:** Sistema de Seguro Internacional Verlaz
- **Versão:** 1.0.0
- **Status:** Produção

### **Documentação**
- README completo
- Código comentado
- Estrutura organizada
- Exemplos de uso

---

## 🏆 **Características Técnicas**

### **Compatibilidade**
- ✅ Chrome, Firefox, Safari, Edge
- ✅ Desktop e Mobile
- ✅ Sem dependências externas
- ✅ Funciona offline

### **Segurança**
- ✅ Validação client-side
- ✅ Sanitização de inputs
- ✅ Prevenção de XSS
- ✅ Dados locais seguros

### **Manutenibilidade**
- ✅ Código organizado
- ✅ Funções modulares
- ✅ Comentários explicativos
- ✅ Estrutura escalável

---

**Desenvolvido para Verlaz - Sistema de Seguro Internacional** 🛡️

