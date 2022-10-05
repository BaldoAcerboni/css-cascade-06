# css-cascade-06
index.html and style.css downloaded from github.
CSS file will have some issues with specificity.
fix it to match the given screenshot without actually modifing any of the actual styles.
later comment on what is done for clarity.

moved .para selector above above .small-para so that .small-para font-size can take precedence as per screen-shot
moved .confirm selector below .button so that .confirm can take desired properties without being overwritten by .button
div.text selector changed to .text and moved above .child so that .child could get desired properties without inteference