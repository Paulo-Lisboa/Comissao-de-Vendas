# 📊 **Calculadora de Comissões**  

Um aplicativo web simples e eficiente para calcular comissões de vendas, bonificações e gerar relatórios. Com ele, você pode adicionar vendedores e clientes, calcular automaticamente as comissões e imprimir ou salvar os resultados de forma profissional.

---

## 🧰 **Funcionalidades**
- **Adicionar Vendedores e Clientes**: Registre informações de vendas diretamente na interface.
- **Cálculo Automático de Comissões**:
  - Baseado em ativações e mensalidades.
  - Bonificação extra para vendas acima de metas definidas.
- **Resumo de Resultados**:
  - Visualize totais de vendas, comissões e bonificações.
  - Relatório detalhado com meses previstos para pagamento.
- **Impressão**:
  - Gere relatórios prontos para imprimir diretamente na sua impressora.
- **Interface Intuitiva**:
  - Campos pré-preenchidos com data atual no formato `DD-MM-YYYY`.
  - Design clean e funcional.

---

## 🚀 **Como usar?**
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/calculadora-comissoes.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd calculadora-comissoes
   ```
3. Abra o arquivo `index.html` no navegador:
   ```bash
   start index.html
   ```

---

## 📝 **Tecnologias Utilizadas**
- **HTML5**: Estrutura semântica e acessível.
- **CSS3**: Design limpo e responsivo.
- **JavaScript**: Lógica do cálculo e interação com o DOM.
- **jsPDF** (opcional): Gerador de relatórios PDF para salvar os resultados.

---

## 🛠️ **Personalizações**
### Alterar Regras de Comissão
Se quiser personalizar os valores ou faixas de comissão, edite o arquivo `script.js`:
```javascript
if (numVendas >= 1 && numVendas <= 6) {
    comissaoAtivacao = totalAtivacoes * 0.1;
} else if (numVendas >= 7 && numVendas <= 9) {
    comissaoAtivacao = totalAtivacoes * 0.15;
}
```

---

## 🌟 **Preview**
Veja como é fácil de usar:

![Preview da Calculadora]([https://via.placeholder.com/800x400?text=Adicionar+uma+imagem+aqui](https://imgur.com/qRFVd16))

---

## 👩‍💻 **Contribuições**
Contribuições são sempre bem-vindas! Sinta-se à vontade para:
- Abrir *issues* com bugs ou sugestões.
- Criar um *pull request* com melhorias no código.

---

## 📜 **Licença**
Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

---

**Feito com ❤️ por [Paulo Lisboa]([https://github.com/Paulo-Lisboa]).**
