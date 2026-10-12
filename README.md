# prima-pr

Il mio primo repository per imparare le pull request.

## Cos'è una pull request

Una pull request (PR) è una proposta di modifica: si lavora su un branch
separato e poi si chiede di unire quelle modifiche al branch principale
(`main`). Prima dell'unione la PR si può rivedere e commentare.

## Il flusso, passo per passo

1. Creare un branch: `git switch -c nome-branch`
2. Modificare i file
3. Salvare le modifiche in un commit: `git add .` e `git commit -m "messaggio"`
4. Inviare il branch su GitHub: `git push -u origin nome-branch`
5. Aprire la PR: `gh pr create`
6. Unire la PR dalla pagina GitHub con **Merge pull request**
