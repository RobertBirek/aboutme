# Analiza Danych EDA Irysów: Eksploracja Domenowa

2025-01-27

Zapraszam do zapoznania się z projektem analizy danych irysów, w którym wykorzystano eksploracyjną analizę danych (EDA). Projekt zawiera konkretne wnioski oraz interesujące obserwacje, pokazujące zależności pomiędzy cechami roślin. To praktyczne podejście do analizy danych, które może być inspiracją do własnych eksperymentów i pogłębiania wiedzy z zakresu Data Science.

<a href="iris.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="iris.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>