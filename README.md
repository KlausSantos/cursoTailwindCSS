# Curso de Tailwind CSS da Alura

## Customização do Tailwind

### Dentro da tag head inserir o código

```
<script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        azul: {
                            claro: '#C5DFFF',
                            escuro: '#061E3c',
                            hover: '#1057B0'
                        },
                    },
                    fontFamily: {
                        inter: ['Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>

```
