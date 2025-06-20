# Pluggy + Mercado Pago (Pessoa Física)

Este notebook demonstra como conectar sua conta Mercado Pago à API da Pluggy para consultar saldo e transações automaticamente.

## Informações
- Mais informações sobre [Pluggy](https://www.pluggy.ai/pt)
- Doc API da [Pluggy] (https://docs.pluggy.ai/reference/auth)

## Pré-requisitos
- Conta criada na [Pluggy](https://dashboard.pluggy.ai/)
- Uma Application criada para obter `Client ID` e `Client Secret`
- Python 3.x com pacote `requests` (e opcionalmente `pandas`)

## Passos

1. **Autentique-se na Pluggy e obtenha sua `apiKey`**
2. **Liste os connectors e encontre o do Mercado Pago**
3. **Gere o link para conectar sua conta Mercado Pago**
4. **Após conectar, obtenha o `itemId` pelo dashboard Pluggy (Applications > Preview Demo)**
5. **Liste as contas vinculadas ao Mercado Pago**
6. **Pegue saldo, informações da conta e transações**
7. **Transações são paginadas, então rode o loop para baixar todas**
8. **(Opcional) Salve os dados em CSV**

## Links uties
- [Dash Pluggy](https://dashboard.pluggy.ai/)
- [Account Pluggy](https://meu.pluggy.ai/account)
- [Demo Pluggy](https://demo.pluggy.ai/?e={email-aqui})

> **Dica:**  
> Para pegar o `itemId`, vá no dashboard Pluggy em Applications > Preview Demo, e copie o valor mostrado ao lado direito.
