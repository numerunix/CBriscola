# CBriscola
Clone in c sharp del progetto briscola.
Attualmente è solo per console, ma è internazionalizzato.

# Come creare localizzazioni
La cosa migliore da fare è usare Visual Studio per windows, che ha il localizzatore di risorse specifico.
Bisogna per prima cosa aprire il progetto in visual studio, poi aprire la cartella Strings. creare la propria cartella usando il formato della lingua a due caratteri (per esempio pt per portoghese o de per tedesco, sono standardizzati), a questo punto copiare il file Resource.rex già tradotto in un'altra lingua all'interno di questa cartella. Adesso basta aprire il file Resources.resx per tradurre, modificando solo la colonna valore.

<img width="166" alt="Immagine 2022-05-24 183923" src="https://user-images.githubusercontent.com/49764967/170088182-ae8ebea9-ba57-4df8-a653-1b6fa29434d0.png">
<img width="1620" alt="Immagine 2022-05-24 184008" src="https://user-images.githubusercontent.com/49764967/170088188-248a572f-9de2-4270-9667-30c8eaca1cf2.png">

In alternativa, è possibile aprire il file Resources.resx con qualsiasi editor di testo, localizzarlo, e poi metterlo nella cartella apposita.
La localizzazione comincia dalla tupla "AdOperaDi".
Fate attenzione a modirficare solo il campo "value" della tupla.

![screen-2022-05-24-18-28-26](https://user-images.githubusercontent.com/49764967/170086921-99ddc6ab-753f-475a-a2eb-f913249e95bb.png)

Va detto che l'autore della localizzazione non è hardcodato, ma è disponibile all'interno del file di localizzazione, e che la GPL obbliga a mantenere i credits, per cui fate i seri e localizzate il più possibile prendendovi solo i vostri credits.

Se volete mandarmi le vostre localizzazioni sono ben felice di aggiungerle al programma originale e di lasciarvi i credits, basta che aprite una pull request su questa piattaforma aggiungendo il file di risorse ed il file xml che i programmi creano.

# Bibliografia
https://docs.microsoft.com/it-it/dotnet/csharp/language-reference/keywords/ref

https://docs.microsoft.com/it-it/dotnet/csharp/language-reference/keywords/interface

https://docs.microsoft.com/it-it/dotnet/api/system.string.compareto?view=net-6.0

https://docs.microsoft.com/en-us/dotnet/api/system.resources.resourcemanager?view=net-6.0

https://livebook.manning.com/book/dotnet-core-in-action/chapter-10/6

https://docs.microsoft.com/it-it/windows-server/administration/linux-package-repository-for-microsoft-software

https://stackoverflow.com/questions/21019144/how-to-create-manual-entry-for-deb-package

https://github.com/numerunix/briscola
