# AI Labs Tracker

Painel estático para acompanhar horários de pico/off-peak e campanhas de desconto de provedores de IA.

## Rodar localmente

Como o projeto não usa build nem dependências, basta abrir `index.html` no navegador. Para testar como um site HTTP:

```bash
python3 -m http.server 8000
```

Depois, acesse <http://localhost:8000>.

## Publicar no GitHub Pages

1. Envie estes arquivos para um repositório no GitHub.
2. Abra **Settings → Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch (por exemplo, `main`) e a pasta **/(root)**.
5. Clique em **Save** e aguarde o endereço aparecer.

O `index.html` já está na raiz para funcionar como entrada do GitHub Pages e encaminha para o painel principal.
