# 💰 Planilha de Gastos Futuros

Uma aplicação web moderna e interativa para controle e gestão de compromissos financeiros futuros, desenvolvida com HTML, CSS e JavaScript vanilla.

## 🚀 Funcionalidades

### 📊 **Dashboard Executivo**
- **Resumo visual** com cards informativos
- **Total geral** de todos os gastos
- **Alertas de vencimentos** (vencidos e próximos 7 dias)
- **Contador de itens** por categoria

### 🔍 **Sistema de Filtros Avançado**
- **Por categoria**: Cartão de Crédito, Empréstimo, Compras, Serviços
- **Por mês**: Visualização temporal organizada
- **Por status**: Vencidos, Próximos ou Em dia
- **Combinação de filtros** para análise detalhada

### ➕ **Adição de Novos Gastos**
- **Formulário intuitivo** com validação
- **Gastos únicos** ou **recorrentes**
- **Cálculo automático** de parcelas
- **Múltiplas frequências**: Mensal, Bimestral, Trimestral, Semestral, Anual

### 🎨 **Interface Moderna**
- **Design responsivo** (desktop e mobile)
- **Indicadores visuais** por status
- **Gradientes e animações** suaves
- **Tema profissional** com cores organizadas

## 📋 Categorias Disponíveis

| Categoria | Descrição | Cor |
|-----------|-----------|-----|
| 🏦 **Cartão de Crédito** | Faturas de cartões | Azul |
| 💳 **Empréstimo** | Financiamentos e empréstimos | Laranja |
| 🛒 **Compras** | Compras parceladas | Verde |
| 📱 **Serviços** | Contas mensais e assinaturas | Roxo |

## 🎯 Status de Pagamento

- 🔴 **Vencido**: Pagamentos em atraso
- 🟡 **Próximo**: Vencimento nos próximos 7 dias  
- 🟢 **Em dia**: Pagamentos futuros

## 📱 Como Usar

### 1. **Visualização Inicial**
- A planilha carrega com dados pré-configurados
- Resumo executivo no topo mostra totais importantes
- Tabela principal organizada por data de vencimento

### 2. **Aplicar Filtros**
```
🔍 Use os filtros no topo para:
• Categoria → Filtrar por tipo de gasto
• Mês → Ver gastos de um período específico  
• Status → Focar em vencidos ou próximos
```

### 3. **Adicionar Novo Gasto**
```
➕ Clique em "Adicionar Gasto"
📝 Preencha o formulário:
   • Nome do gasto (obrigatório)
   • Categoria (obrigatório) 
   • Valor em R$ (obrigatório)
   • Data de vencimento (obrigatório)
   • Observações (opcional)

🔄 Para gastos recorrentes:
   • Marque "Gasto recorrente"
   • Defina quantidade de parcelas
   • Escolha a frequência
```

### 4. **Gastos Recorrentes**
O sistema calcula automaticamente:
- **Datas futuras** baseadas na frequência escolhida
- **Numeração das parcelas** (1/12, 2/12, etc.)
- **Observações detalhadas** para cada parcela

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura e semântica
- **CSS3**: Design responsivo e animações
- **JavaScript**: Lógica de negócio e interatividade
- **LocalStorage**: Persistência de dados (futuro)

## 📊 Recursos Técnicos

### **Cálculos Automáticos**
- Soma de valores por categoria
- Contagem de itens vencidos/próximos
- Geração de datas recorrentes
- Formatação monetária brasileira

### **Validações**
- Campos obrigatórios
- Valores numéricos positivos
- Datas futuras (não permite passado)
- Quantidade mínima/máxima de parcelas

### **Responsividade**
- Grid system flexível
- Breakpoints para mobile
- Elementos adaptativos
- Usabilidade em touch

## 🎨 Personalização

### **Cores por Categoria**
```css
.categoria.cartao-credito { color: #1976d2; }
.categoria.emprestimo { color: #f57c00; }  
.categoria.compras { color: #388e3c; }
.categoria.servicos { color: #7b1fa2; }
```

### **Status de Alertas**
```css
.vencido { border-left: 4px solid #f44336; }
.proximo-vencimento { border-left: 4px solid #ff9800; }
```

## 📈 Dados de Exemplo

A planilha vem com dados pré-configurados:
- Cartões de crédito (Santander, Itaú, Nubank)
- Empréstimos 99pay com parcelas
- Compras Mercado Livre
- Serviços VIVO recorrentes

## 🔮 Funcionalidades Futuras

- [ ] **Exportação** para Excel/PDF
- [ ] **Gráficos** de evolução mensal
- [ ] **Alertas** por email/WhatsApp
- [ ] **Categorias customizadas**
- [ ] **Backup** em nuvem
- [ ] **Múltiplas moedas**
- [ ] **Histórico** de pagamentos
- [ ] **Calculadora** de juros

## 💡 Dicas de Uso

### **Organização Eficiente**
1. **Categorize corretamente** cada gasto
2. **Use observações** para detalhes importantes
3. **Configure recorrências** para pagamentos fixos
4. **Monitore regularmente** os status de vencimento

### **Controle Financeiro**
- **Foque nos vencidos** primeiro (filtro vermelho)
- **Prepare-se para próximos** (filtro amarelo)  
- **Planeje gastos futuros** usando o resumo
- **Use filtros mensais** para orçamento

## 📞 Suporte

Para dúvidas ou sugestões:
- Desenvolvido com ❤️ para controle financeiro pessoal
- Interface intuitiva e autoexplicativa
- Documentação completa neste README

---

## ⚡ Quick Start

1. **Abra** o arquivo HTML no navegador
2. **Explore** os dados de exemplo
3. **Teste** os filtros disponíveis  
4. **Adicione** seus próprios gastos
5. **Monitore** regularmente seus vencimentos

**🎉 Pronto! Você está no controle das suas finanças!**