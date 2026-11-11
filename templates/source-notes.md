
# {{title}} 

**Data:** {{date | format("DD.MM.YYYY")}}

**Autorzy:** {{authors}}

## Definitions

{%- for a in annotations | filterby("colorCategory", "contains", "Orange") %}
{% if a.annotatedText %}
> <span style="color: #F19837;">“{{a.annotatedText}}” ([PDF](zotero://open-pdf/library/items/{{a.attachment.itemKey}}?page={{a.page}}&annotation={{a.id}})) ({{authors}}, {{date}}, p. {{a.page}})</span>
{%- endif %}
{% if a.comment %}
{{a.comment}}
{%- endif %}
{% endfor %}
## Important

{%- for a in annotations | filterby("colorCategory", "contains", "Yellow") %}
{% if a.annotatedText %}
> <span style="color: #FFD400;">“{{a.annotatedText}}” ([PDF](zotero://open-pdf/library/items/{{a.attachment.itemKey}}?page={{a.page}}&annotation={{a.id}})) ({{authors}}, {{date}}, p. {{a.page}})</span>
{%- endif %}
{% if a.comment %}
{{a.comment}}
{%- endif %}
{% endfor %}
## Interesting points

{%- for a in annotations | filterby("colorCategory", "contains", "Green") %}
{% if a.annotatedText %}
> <span style="color: #5FB236;">“{{a.annotatedText}}” ([PDF](zotero://open-pdf/library/items/{{a.attachment.itemKey}}?page={{a.page}}&annotation={{a.id}})) ({{authors}}, {{date}}, p. {{a.page}})</span>
{%- endif %}
{% if a.comment %}
{{a.comment}}
{%- endif %}
{% endfor %}
## Doubts

{%- for a in annotations | filterby("colorCategory", "contains", "Red") %}
{% if a.annotatedText %}
> <span style="color: #FF6666;">“{{a.annotatedText}}” ([PDF](zotero://open-pdf/library/items/{{a.attachment.itemKey}}?page={{a.page}}&annotation={{a.id}})) ({{authors}}, {{date}}, p. {{a.page}})</span>
{%- endif %}
{% if a.comment %}
{{a.comment}}
{%- endif %}
{% endfor %}
## Ideas

{%- for a in annotations | filterby("colorCategory", "contains", "Purple") %}
{% if a.annotatedText %}
> <span style="color: #A28AE5;">“{{a.annotatedText}}” ([PDF](zotero://open-pdf/library/items/{{a.attachment.itemKey}}?page={{a.page}}&annotation={{a.id}})) ({{authors}}, {{date}}, p. {{a.page}})</span>
{%- endif %}
{% if a.comment %}
{{a.comment}}
{%- endif %}
{% endfor %}
## Articles

{%- for a in annotations | filterby("colorCategory", "contains", "Blue") %}
{% if a.annotatedText %}
> <span style="color: #2EA8E5;">“{{a.annotatedText}}” ([PDF](zotero://open-pdf/library/items/{{a.attachment.itemKey}}?page={{a.page}}&annotation={{a.id}})) ({{authors}}, {{date}}, p. {{a.page}})</span>
{%- endif %}
{% if a.comment %}
{{a.comment}}
{%- endif %}
{% endfor %}
## I don't understand

{%- for a in annotations | filterby("colorCategory", "contains", "Magenta") %}
{% if a.annotatedText %}
> <span style="color: #E56EEE;">“{{a.annotatedText}}” ([PDF](zotero://open-pdf/library/items/{{a.attachment.itemKey}}?page={{a.page}}&annotation={{a.id}})) ({{authors}}, {{date}}, p. {{a.page}})</span>
{%- endif %}
{% if a.comment %}
{{a.comment}}
{%- endif %}
{% endfor %}