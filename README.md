Para la construccion de web componentes se utilizan 4 web APIs

## 1 HTMLElement

me permite crear un objeto con la estructura neccesaria para inyectar el codigo en el DOM
en la carpeta **Custom-Elements** podemos ver algunos ejemplos de como usarlo

## 2 Template

Me permite encapsuar el codigo dentro de un document-fragment

podremos ver un ejemplo en la carpeta **Templates**

## 3 Shadow Dom

Me permite encapsular los componentes para hacer un ecosistema porpio e independiente del elemento

podremos ver un ejemplo en la carpeta **shadowDom**

## Content Slot

nos ayuda a manipular datos

la etiqueta slot va dentro del componente y el contenido que se quiera manipular va dentro de la etiqueta del componete

```html
<my-element-aslot>
    Este texto saldra en la etiqueta slot, texto puesto fuera del componente
</my-element-aslot>
```

tambien puede tener nombres los slots

```html
<my-element-multislot>
    <span slot="title">
        Este texto saldra en la etiqueta slot1(title), texto puesto fuera del
        componente
    </span>
    <span slot="texto">
        Este texto saldra en la etiqueta slot2(texto), texto puesto fuera del
        componente
    </span>
</my-element-multislot>
```

podremos ver un ejemplo en la carpeta **Slot**
