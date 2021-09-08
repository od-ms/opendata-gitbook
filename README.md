---
description: Eine Testseite mit verschiedenen Inhalten.
---

# Initial page

## Open Data

Testen was man hier so machen kann..

{% hint style="info" %}
Hints finde ich ja turbo cool! Wie macht man denn sowas in Markdown? Das würd ich ja gern mal sehen.
{% endhint %}

{% tabs %}
{% tab title="First Tab" %}
Öhhm .. Tabs, seriously?
{% endtab %}

{% tab title="Außerdem" %}
Außerdem kann auf dem zweiten Tab auch was stehen
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
Noch ein Hint weil's so schön ist!
{% endhint %}

| Tabelle | Spalte \#2 |
| :--- | :--- |
| Könnte hier was stehen | Und hier auch? |
| Geht noch was | Jau |
| Mit drei Zeilen | und Zahlen? 234€ |

### Codebeispiel

{% code title="hello.sh" %}
```bash
# Code geht auch klar
$yo = "mama";
```
{% endcode %}

{% api-method method="get" host="https://" path="api.muenster-jetzt.de/events" %}
{% api-method-summary %}
Daten holen
{% endapi-method-summary %}

{% api-method-description %}
Events Methode
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="location" type="string" required=false %}
ID vom Ort
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

