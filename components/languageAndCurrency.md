# Language and currency

!> We are combining both languages and currencies selection into one single element to centralise the action to configure the user localization settings.

!> SEO concerns: the links to the lang and curr need to appear somewhere. It can be in the Javascript. 

![langAndCur](langHeader.png ':min-width=400px') ![langAndCur](langFooter.png ':min-width=400px')


![Overlay](languageAndCurrency-overlay.png)
 
## Settings overlay
   You get there tapping the component. It will trigger a `is-active` class in the overlay.
   
   **Note:** The overlay shows up with a transition in 2 times.
   
   ![Overlay](overlay2Times.jpg)
    
   ### Default state
   English language and EUR currency by default.
   
   ### Action triggers
   - **Cross:** Goes back to previous page. No transition needed.
   - **Language input:** Triggers native mobile select for Language options.
   - **Currency input:** Triggers native mobile select for Currency options.
   - **Apply CTA:** Applies the selected settings and returns to the previous page. No transition needed.


 
## Settings overlay with Language active
   You get there by tapping language select. We will use the native `<select>`
  
   ### Content
   The language flag ( ![langAndCur](langFlag.png ':zoom:100%') ) changes according to the selected option. Also, the options list has two sections: "Popular languages" with a top 5 (English, Spanish, Deutsch, French, Italian) and "All languages".</span>

 
## Settings overlay with Currency active
   You get there by tapping currency select. We will use the native `<select>`
    
   ### Content
   The options list has two sections: "Popular currencies" with a top 3 (EUR, GBP, USD) and "All currencies".