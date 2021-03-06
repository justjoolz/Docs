# Balancer

![](../../.gitbook/assets/group-277.png)

{% tabs %}
{% tab title="Overview" %}
{% hint style="info" %}
### A constant mean market maker is a generalization of a constant product market maker, allowing for more than two assets and weights outside of 50/50.
{% endhint %}

![](../../.gitbook/assets/image.png)

 _where **R** is the **reserves** of each asset, **W** is the **weights** of each asset, and **k** is the **constant**. In other words, in the absence of fees, constant mean markets ensure that the **weighted geometric mean** of the reserves remains constant._

| **Balancer Protocol** | system of smart contracts for automated token exchange on Ethereum. |
| :--- | :--- |
| **Balancer Exchange** | opensource front-end interface for traders and liquidity providers to easily interact with Balancer smart contracts. |
| **Balancer Pool** | Exchange contract containing ERC20 pairs. |
| **Liquidity Providers**  | can be anyone who is able to supply equal values of WETH or any ERC-20 token included in a Balancer exchange contract. |
| **BPool** | ERC20 tokens which are minted by LPs from the exchange contract and can be used to withdraw their proportion of the liquidity at any time. |
| **Traders** | exchange one asset for another asset. |
| **Arbitrageurs** | maintain the price of assets within that portfolio in accordance with the market price in exchange for a profit. |
{% endtab %}
{% endtabs %}

