# Language and Currency

{% hint style="info" %}
We are combining both languages and currencies selection into one single element to centralise the action to configure the user localisation settings.
{% endhint %}

{% hint style="info" %}
SEO concerns: the links to the lang and curr need to appear somewhere. It can be in the Javascript.
{% endhint %}

![:min-width=400px](../.gitbook/assets/langheader%20%281%29.png) ![:min-width=400px](../.gitbook/assets/langfooter%20%281%29.png)

![Overlay](../.gitbook/assets/languageandcurrency-overlay%20%281%29.png)

## Settings overlay

You get there tapping the component. It will trigger a `is-active` class in the overlay.

**Note:** The overlay shows up with a transition in 2 times.

![Overlay](../.gitbook/assets/overlay2times%20%281%29.jpg)

### Default state

English language and EUR currency by default.

### Action triggers

* **Cross:** Goes back to previous page. No transition needed.
* **Language input:** Triggers native mobile select for Language options.
* **Currency input:** Triggers native mobile select for Currency options.
* **Apply CTA:** Applies the selected settings and returns to the previous page. No transition needed.

## Settings overlay with Language active

You get there by tapping language select. We will use the native `<select>`

### Content

The language flag \( ![:zoom:100%](../.gitbook/assets/langflag.png) \) changes according to the selected option. Also, the options list has two sections: "Popular languages" with a top 5 \(English, Spanish, Deutsch, French, Italian\) and "All languages".&lt;/span&gt;

## Settings overlay with Currency active

You get there by tapping currency select. We will use the native `<select>`

### Content

The options list has two sections: "Popular currencies" with a top 3 \(EUR, GBP, USD\) and "All currencies".

