# NexaMed-Secretaire-Releases

Depot de releases Velopack du poste **NexaMed Secretariat** (packId : com.scilicode.nexamed.secretaire).

Alimente par le workflow `release-velopack.yml` du depot source `scilicode-sys/NexaMed` : ne rien modifier ici a la main.
Les `Setup.exe`, `.nupkg` et `releases.<canal>.json` sont regeneres a chaque course. Le poste lit ce depot par son URL absolue
(`MiseAJourVelopack.NexaMed-Secretaire-Releases`), et le jeton qui y ecrit ne couvre que lui.
