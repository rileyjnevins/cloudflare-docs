---
title: HTTP DDoS Attack Protection
pcx-content-type: concept
order: 2
---

# HTTP DDoS Attack Protection Managed Ruleset

The Cloudflare HTTP DDoS Attack Protection Managed Ruleset is a set of pre-configured rules used to match [known DDoS attack vectors](/about/attack-coverage) at layer 7 (application layer) on the edge. Cloudflare updates the list of rules in the Managed Ruleset on a regular basis.

The HTTP DDoS Attack Protection Managed Ruleset is always enabled — you can only customize its behavior.

The HTTP DDoS Attack Protection Managed Ruleset provides users with increased observability into L7 DDoS attacks mitigated by Cloudflare, informing users of ongoing or past attacks. The [Firewall Analytics dashboard](https://developers.cloudflare.com/waf/analytics), available at **Firewall** > **Overview**, will display additional information on the types of L7 DDoS attacks detected for a specific zone.

## Ruleset configuration

You can adjust the behavior of the rules in the Managed Ruleset by modifying the following parameters:

* The performed **action** when an attack is detected
* The **sensitivity** of attack detection mechanisms

<Aside type="note" header="Note">

Certain actions or sensitivity levels may not be available to all Cloudflare plans.

</Aside>

To adjust rule behavior, do one of the following:

* [Configure HTTP DDoS Attack Protection in the dashboard](/managed-rulesets/http/configure-dashboard).
* [Configure HTTP DDoS Attack Protection Managed Ruleset overrides via API](/managed-rulesets/http/configure-api).

For more information on the available configuration parameters, see [Managed Ruleset parameters](/managed-rulesets/http/override-parameters).

## Availability

The HTTP DDoS Attack Protection Managed Ruleset protects Cloudflare customers on all plans, and all customers can customize the ruleset.

## Related Cloudflare products

To block additional L7 attacks you can use other Cloudflare products like the [Cloudflare WAF](https://developers.cloudflare.com/waf/).
