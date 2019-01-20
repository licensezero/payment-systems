# Stripe

## Aggregation

<https://stripe.com/us/ssa>:

> When you accept payment card Transactions, Network Rules specifically prohibit you from ... (iv) acting as a payment facilitator, intermediary or aggregator, or otherwise reselling Payment Processing Services on behalf of others, ....

[Response to support question](https://support.stripe.com/questions/marketplace-not-using-stripe-connect-am-i-aggregating):

> Stripe does have some restrictions on businesses accepting payments on behalf of other businesses, a practice sometimes known as "aggregation."
>
> Aggregation is, however, a pretty fuzzy term. Much of it depends on customer expectations -- who they expect to be buying from, whether you're handling customer support, refunds, disputes, and so on. You shouldn't immediately assume you're in violation of our terms if you're a marketplace; many that use Stripe are not.
>
> It may be useful for you to think about the following questions:
>
> - **Who do customers think they are buying from? In other words, would the customer be surprised or confused to see your business name on their credit card statement?**
>
>   It should be very clear to your customers that they're paying <em>you</em> and not a seller in your marketplace. If a customer is surprised to see your business name on their statement, it probably makes more sense for the seller to be processing these payments instead (<a href="https://stripe.com/connect">Stripe Connect</a> works pretty well for this purpose).
>
> - **What type of services or goods are customers buying from you? Are you verifying that these goods or services follow Stripe's Terms of Service and confirming that your suppliers or vendors are legitimately providing them?**
>
>   If you're accepting payments for goods or services that others are providing, you need to be curating these such that you're not accepting payments for anything that is against Stripe's <a href="https://stripe.com/terms">Terms of Service</a>, and you should be able to confirm in some way that the good or service was actually provided to the customer. In addition, you should be <a href="https://support.stripe.com/questions/how-do-i-verify-transfer-recipients">verifying the identity</a> of any person or business you're paying out with Stripe.
>
> - **Who handles support requests, disputes, or refunds?**
>
>   Since customers are buying from you, you're responsible for handling all support requests, disputes, and refunds.
>
> If your business model doesn't fit with these guidelines, Stripe Connect may make more sense for you. As always, please feel free to <a href="/email">get in touch</a> with us; we're happy to help clarify any points or help you determine which one might work best for your business.
