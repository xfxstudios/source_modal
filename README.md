# source_modal
Aporte de TrinityCore en Foros del Web
http://www.forosdelweb.com/f179/aporte-window-modal-personalizable-1160996/

> Ejemplo de configuración del Modal

```Windows1 = new WindowsInterface({
                id:"muestraID",
                clases:"claseAdicional1 claseAdicional2",
                claseTitulo:"claseTitulo",
                claseTexto:"claseTexto"
            });
            Windows1.init(null, "Mi Ventana", 250, 200, 600, 450, {minimize: true, maximize: true, close: true}, true);
            Windows1.SetContent().Message("<p>Hola Mundo!</p>");
            Windows1.SetContent().FontSize("p", "1.5vmin");
```
