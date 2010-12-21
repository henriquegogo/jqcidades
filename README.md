# Plugin jQuery que alimenta os estados e as cidades do Brasil.

## Para utilizar:

    <script src='http://code.jquery.com/jquery-1.4.4.min.js' type="text/javascript" charset="utf-8"></script>
    <script src="jqcidades.js"></script>
    <script>
    $(document).ready(function() {
      $('select#estado').carregaCidades('select#cidade');
    });
    </script>

    <select id="estado"></select>
    <select id="cidade"></select>

