# A/B Experiment Brief, Riverty business-unit case

## Parameters
| Parameter | Decision |
|---|---|
| Feature under test | Riverty card |
| Persona | A heavy BNPL user (8 purchases a month) and Riverty Flex user who also carries Klarna and PayPal and falls back to her debit cards everywhere else. |
| Expected outcome | Persona can use card everywhere and pay after delivery |
| Primary success metric | Activly usage of  card |
| Baseline rate | 92 |
| Guardrail metric | Number of successful purchase |
| Guardrail boundary | 92% |
| Second guardrail | · |
| Minimum Detectable Effect | 5% |
| Sample size per arm | 326 |
| Traffic split | 50/50 |
| Test duration | 1 month |
| Significance threshold | 95% |

## Control vs. Variant
- **Control (A):** Moment of Misery is the till. Online she uses pay later on almost every order, but in a shop she has no way to decide later and pay afterwards from home.
- **Variant (B):** Enable post-purchase decision for in-store card taps. After a tap at any terminal, the purchase appears in the app with a “decide” action, and she picks her existing Flex option from home.
- **Held constant (isolation check):** Online card behaviour and notifications,Flex limit, plan types, pricing and fees

## Hypothesis
> I believe that Riverty card for A heavy BNPL user (8 purchases a month) and Riverty Flex user who also carries Klarna and PayPal and falls back to her debit cards everywhere else. will result in Persona can use card everywhere and pay after delivery, as measured by a 5% change in Activly usage of  card within 1 month. We will protect Number of successful purchase throughout the test.

## Shipping criteria
> We will **ship** if Activly usage of  card improves by ≥ 5% at 95% and Number of successful purchase does not reach 92% after 1 month.
> We will **iterate** if direction is positive but lift is below the MDE.
> We will **kill** if the primary metric shows no improvement or moves negatively.
> The read date is fixed at the end of 1 month, no results reviewed before this date.
