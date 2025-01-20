![](https://medias.revistaoeste.com/wp-content/uploads/2023/08/FreePix.jpg.webp)

## Default Analysis

This challenge proposes the creation of a predictive model that calculates the probability of default for recurring customers on new credit applications. For this, 3 relational databases are provided containing information about customers and their transactions. The goal is to use this information to build a credit score model that helps companies make credit approval or denial decisions.


### Dictionary:

1) **Table info:**
    - **ID_CLIENTE:** Unique customer identifier.
    - **SAFRA_REF:** Sample reference month.
    - **RENDA_MES_ANTERIOR:** Revenue declared by the customer in the previous month.
    - **NO_FUNCIONARIOS:** Number of employees reported by the customer in the previous month.

2) **Table cadastro:**
    - **ID_CLIENTE:** Unique customer identifier.
    - **DATA_CADASTRO:** Registration date in the system.
    - **DDD:** Customer's telephone area code.
    - **FLAG_PF:** Indicates whether the customer is an individual (X) or a legal entity (NaN).
    - **SEGMENTO_INDUSTRIAL:** Indicates the sector in which the customer operates.
    - **DOMINIO_EMAIL:** Indicates the customer's email domain, used in the registration.
    - **PORTE:** Company size.
    - **CEP_2_DIG:** Indicates the first two digits of the zip code of the registered address.

3) **Table pagamentos:**
    - **ID_CLIENTE:** Unique customer identifier.
    - **SAFRA_REF:** Sample reference month.
    - **DATA_EMISSAO_DOCUMENTO:** Date of issuance of the credit note.
    - **DATA_VENCIMENTO:** Due date for loan payment.
    - **VALOR_A_PAGAR:** Amount to be paid for the credit note.
    - **TAXA:** Loan interest rate.
    - **DATA_PAGAMENTO:** Date on which the customer made the payment of the credit note.


*Python 3.11.10*