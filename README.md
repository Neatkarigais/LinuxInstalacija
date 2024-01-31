<h1> Linux palaišana uz USB atmiņas </h1>

Šajā GitHubā izveidota pamācība Linux palaišana uz USB atmiņas. Procesā ir nepieciešama viena USB atmiņa, kurā viss Linux tiks palaists.

<h2> Instalēšanas process </h2>
<h3> 1. Rufus un Linux failu lejupielādēšana </h3>

No sākuma ir nepieciešams lejupielādēt Rufus un attiecīgā Linuxa iso failu. Rufus ir programma, kas ļaus instalēt Linuxu uz USB atmiņas, izmantojot Linuxa iso failu. Rufus var lejupielādēt, uzspiežot uz https://rufus.ie/lv/.
Šeit tiks izmantots Ubuntu Linux, kura lejupielādes links ir pieejams šeit: https://www.linuxmint.com/edition.php?id=311.

<h3> 2. Rufus palaišana </h3>

Kad Rufus ir lejupielādēts, vajag uzspiest uz tā, pēc kā atveras logs.

&nbsp; <img src="https://raw.githubusercontent.com/Neatkarigais/LinuxInstalacija/main/Rufus.PNG" height="538" width="478" />

<h3> 3. Linuxa palaišana uz BIOS </h3>

Kad nepieciešamie faili ir lejupielādēti, tad var palaist BIOS. BIOS var palaist, atkārtoti spiežot uz DEL vai F11 vai F12 pogas (atkarīgs no BIOS). Kad tas ir izdarīts vajadzētu būt redzamai šādai bildei.

&nbsp; <img src="https://raw.githubusercontent.com/Neatkarigais/LinuxInstalacija/main/1706734925213.jpg" height="307" width="409" />

Tālāk nepieciešams atrast sadaļu BIOS/BOOT, kur aprakstītas vietas, no kurām palaižas BIOS.

&nbsp; <img src="https://raw.githubusercontent.com/Neatkarigais/LinuxInstalacija/main/1706734925200.jpg" height="307" width="409" />

Attiecīgi nepieciešams samainīt BOOT Option #1 uz to USB, kuru satur attiecīgie faili. Šajā gadījumā tas ir UEFI Kingston. Izvēloties šo opciju, vajag aizvērt saglabāt un aizvērt BIOS. Ja viss ir izdarīts pareizi, vajadzētu palaisties Linuxam nevis Windows.

&nbsp; <img src="https://raw.githubusercontent.com/Neatkarigais/LinuxInstalacija/main/1706734925189.jpg" height="307" width="409" />

Tagad var izvēlēties pirmo opciju, pēc kā visam vajadzētu būt palaistam un gatavam. Tagad tev ir strādājošs Linux, apsveicu! :)

&nbsp; <img src="https://raw.githubusercontent.com/Neatkarigais/LinuxInstalacija/main/1706734925177.jpg" height="307" width="409" />

