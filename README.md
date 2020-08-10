# Diffrence_Partial_RenderPartial_MVC

SIMILARITIES AND DIFFERENCE BETWEEN HTML.PARTIAL AND HTML.RENDERPARTIAL
•	Both Html.Partial and Html.RenderPartial can be used to access or display a partial view in a view

Html.Partial
  Method that returns MVCHtmlString	means Html.Partial returns html string.
  Rendered Partial view result can be stored in string variable.
  Html.Partial injects the html string of the partial view into the main view.
  Html.Partial() need not to be inside the braces.
  Performance is slow
  

Html.RenderPartial

  Method without any return value, it means it returns void.
  Rendered Partial view result cannot be stored in string variable.
  Html.RenderPartial writes html in the response stream.
  Perform is faster compared with HtmlPartial().
  Fast in access
  Html.RenderPartial must be inside braces @{ }.
