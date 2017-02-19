# HTML.Maid
C# to HTML Converter

sample code to convert c# to HTML

HtmlDocument doc = new HtmlDocument();

doc.Add(new HtmlTagBuilder(HTML.Maid.Helpers.HtmlTags.Div).AddHtml("Welcome"));

doc.GetHtml();
