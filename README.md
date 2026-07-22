# MOTTA MEMTEST v1.0

Utilitário avançado desenvolvido em Python para diagnóstico de memória RAM, verificação detalhada de pentes físicos por slot (A1, A2, B1, B2) e teste de estresse no Windows.

---

## 📸 Telas do Sistema

### Menu Principal e Informações
* Interface principal estilizada em cores com suporte a execução direta, diagnóstico de hardware e monitoramento de memória.

<img width="979" height="512" alt="image" src="COLE_O_LINK_DA_SUA_IMAGEM_AQUI" />

---

## 🚀 Funcionalidades

* **Informações Detalhadas:** Leitura exata da posição no slot físico (`A1`, `A2`, `B1`, `B2`, etc.), capacidade, velocidade (clock), fabricante, part number e fator de forma de cada pente de RAM.
* **Ferramenta Nativa do Windows:** Atalho direto para agendar o diagnóstico oficial de memória (`mdsched`).
* **Teste de Estresse (20s):** Executa alocação controlada de blocos de memória e teste de largura de banda com barra de progresso em tempo real.
* **Status do Sistema:** Monitoramento em tempo real do uso total, disponível e percentual da memória RAM.
* **Controle de Privilégios:** Verificação e solicitação automática de permissões de Administrador ao iniciar.
* **Interface Dinâmica:** Estilização visual em cores via `colorama`.

---

## 🛠️ Como Usar

1. Acesse a aba de **Releases** do repositório.
2. Baixe o arquivo executável (`MOTTAMEMTEST.exe`).
3. Clique com o botão direito no executável e selecione **Executar como Administrador** para garantir a leitura completa dos pentes de RAM via WMI.
4. Utilize o menu interativo conforme as opções disponíveis na tela.

---

## ⚙️ Tecnologias Utilizadas

* **Python**
* **Colorama**
* **WMI / Subprocess / Ctypes**

---

## 📜 Licença
Aplicativo distribuído por Eduardo Motta. Todos os direitos reservados.

## 🤝 Apoie o Desenvolvedor
Se este software te ajudou a otimizar sua máquina, considere apoiar o projeto com um PIX.

**Chave PIX (E-mail - Qualquer Valor):**
`mottatshirts@jim.com`

**PIX Copia e Cola (Valor Fixo R$ 5,00):**
```text
00020101021226840014BR.GOV.BCB.PIX0136dbf0d223-9202-4aaa-b881-cce9603f8fc20222Pagamento mottatshirts52040000530398654045.005802BR5925CARLOS EDUARDO ROLIM DA M6005BELEM62290525QRCCIICLZgxrN6aElFvgLxPOC63044CBF
