Link do figma com a paleta de cores: https://www.figma.com/design/5nUPUlqQ21PcmtgNO9bFhg/Sem-t%C3%ADtulo?node-id=0-1&t=FTsI0tdPrA4xadcX-1
### Cores Primárias

```css
/* Azul - Identidade Principal */
--blue-50:  #eff6ff   /* Fundos claros, degradês */
--blue-100: #dbeafe   /* Fundos de ícones */
--blue-600: #2563eb   /* Ícones, elementos interativos */
--blue-900: #1e3a8a   /* Títulos principais */

/* Índigo - Degradê */
--indigo-100: #e0e7ff /* Fundo degradê complementar */
```

### Cores Secundárias

```css
/* Verde - Ações Positivas */
--green-100: #dcfce7  /* Fundos verdes claros */
--green-600: #16a34a  /* Ícones e ações de sucesso */

/* Vermelho - Ações Destrutivas */
--red-500: #ef4444    /* Ícones de alerta */
--destructive: #d4183d /* Botões destrutivos */
```

### Cores Neutras

```css
/* Escala de Cinza */
--white:    #ffffff   /* Fundos de cards */
--gray-50:  #f9fafb   /* Fundos alternativos */
--gray-100: #f3f4f6   /* Bordas suaves */
--gray-400: #9ca3af   /* Elementos inativos */
--gray-500: #6b7280   /* Textos secundários */
--gray-600: #4b5563   /* Descrições */
--gray-700: #374151   /* Textos principais */
--gray-900: #111827   /* Textos de alto contraste */
--black:    #030213   /* Elementos de máximo contraste */
```

### Gradientes

```css
/* Gradiente de Fundo Principal */
background: linear-gradient(135deg, #eff6ff 0%, #e0e7ff 100%);
/* Classe Tailwind: bg-gradient-to-br from-blue-50 to-indigo-100 */
```

### Uso de Cores

| Elemento | Cor | Código |
|----------|-----|--------|
| Fundo principal | Gradiente azul-índigo | `from-blue-50 to-indigo-100` |
| Títulos principais | Azul escuro | `text-blue-900` |
| Botões primários | Preto | `bg-primary` (#030213) |
| Ícones principais | Azul médio | `text-blue-600` |
| Textos descritivos | Cinza médio | `text-gray-600` |
| Textos secundários | Cinza claro | `text-gray-500` |
| Fundos de ícones | Azul claro | `bg-blue-100` |
| Cards | Branco | `bg-white` |

---

## Tipografia

### Família de Fontes

```css
font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', 
             Roboto, 'Helvetica Neue', Arial, sans-serif;
