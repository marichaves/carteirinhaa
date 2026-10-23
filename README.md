# Modelo demonstrativo de CIE

Página estática de demonstração visual. Não verifica matrícula ou identidade e não emite documentos ou certificados válidos.

Site ativo na conta Vercel da Mariana: https://cie-demonstracao-two.vercel.app

Painel do projeto: https://vercel.com/marichaves-projects/cie-demonstracao

Repositório privado: https://github.com/Gunoch/cie-demonstracao

Abra `index.html` no navegador. A foto está incorporada ao HTML e não depende de arquivos externos.

## Publicação

O projeto está no plano gratuito da conta `marichaves`, no escopo `marichaves-projects`. Mariana é a proprietária do projeto na Vercel e possui permissão de escrita no GitHub.

Projeto estático, sem comando de build, com saída no diretório raiz.

Na máquina da Mariana, com a CLI autenticada na conta dela:

```powershell
npx vercel login
npx vercel deploy --prod --yes --project cie-demonstracao --scope marichaves-projects
```

As alterações devem ter commits de autoria da própria Mariana, pois a Vercel verifica a autoria ao publicar em projetos Hobby.

A conexão automática do repositório privado ainda depende de autorizar o acesso da integração Vercel/GitHub. Atualizações no GitHub não geram deploy automático até essa conexão ser concluída.

O endereço anterior https://cie-demonstracao.vercel.app permanece como cópia na conta Gunoch; o endereço acima é o projeto controlado pela Mariana.