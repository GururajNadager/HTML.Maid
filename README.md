# HTML.Maid
C# to HTML Converter

sample code to convert c# to HTML

using Html.Maid;
HtmlDocument doc = new HtmlDocument();

doc.Add(new HtmlTagBuilder(HtmlTags.Div).AddHtml("Welcome to HTML.Maid"));

doc.GetHtml();
