<h1 align="center">Hi 👋, I'm Youri Mulders</h1>
<h3 align="center">Software Developer Student</h3>

<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nextjs.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> <a href="https://unity.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/unity3d/unity3d-icon.svg" alt="unity" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=yourimulders1&show_icons=true&locale=en&layout=compact" alt="yourimulders1" /></p>

# 📋 PLANNIFY - Volledige Functionaliteit & Gebruikershandleiding

Dit document beschrijft elke functie, knop, pagina en mogelijkheid van het Plannify order management systeem.

---

## 📖 Systeemoverzicht

Plannify is een geavanceerd order management systeem speciaal ontwikkeld voor Parthos. Het systeem biedt een complete oplossing voor het beheren, monitoren en verwerken van productieorders met uitgebreide aanpassingsmogelijkheden.

### 🎯 Hoofddoelstellingen
- **Real-time orderoverzicht** voor alle betrokkenen
- **Flexibele dashboards** aangepast aan verschillende afdelingen
- **Geautomatiseerde import** van orderbestanden uit BAAN systeem
- **Barcode scanning** voor productietracking
- **Gebruikersspecifiek rechtenbeheer**
- **Uitgebreid notificatiesysteem**

---

## 👥 Gebruikersrollen & Toegangsrechten

### 🔐 BEHEERDER (Administrator)
Het hoogste toegangsniveau met volledige systeemcontrole:
- **Volledige ordertoegang**: Alle orders bekijken, bewerken en verwijderen
- **Gebruikersbeheer**: Accounts aanmaken, bewerken en deactiveren
- **Rechtenbeheer**: Column permissions en paginatoegang instellen
- **Systeemconfiguratie**: Alle instellingen aanpassen
- **Prioriteitsbeheer**: Orders markeren als hoogprioriteit
- **Vergrendelingsfunctie**: Orders vergrendelen voor bewerking
- **Gearchiveerde pagina's**: Toegang tot gearchiveerde custom pages
- **Import notificaties**: Systeem-brede berichten maken
- **Admin panel**: Speciale beheerdersinterface

### 📋 PLANNER
Uitgebreide planningsmogelijkheden:
- **Order management**: Orders bekijken en bewerken
- **Prioriteitsbeheer**: Orders markeren als hoogprioriteit
- **Vergrendelingsfunctie**: Orders vergrendelen tijdens planning
- **Aangepaste dashboards**: Eigen planning-overzichten maken
- **Leverdata**: Leverdata en tijdsinschattingen bijwerken
- **Status wijzigingen**: Order status aanpassen
- **Planning velden**: Toegang tot planning-specifieke informatie

### 💼 SALES
Verkoop-gerichte toegang:
- **Orderinzicht**: Orders bekijken met focus op verkoop
- **Klantinformatie**: Uitgebreide klantgegevens bekijken
- **Verkoop velden**: Specifieke verkoop-gerelateerde velden bewerken
- **Status tracking**: Voortgang volgen voor klantcommunicatie
- **Verkoop dashboards**: Custom dashboards voor verkoop overzichten
- **Beperkte bewerking**: Alleen verkoop-relevante velden aanpassen

### 📱 SCANNER
Productievloer toegang:
- **Barcode scanning**: Volledige scan functionaliteit
- **Scan pagina's**: Toegang tot alle scan-type interfaces
- **Productie updates**: Order status bijwerken via scanning
- **Scan historie**: Overzicht van eigen scan activiteiten
- **Productie velden**: Toegang tot productie-gerelateerde informatie
- **Mobile interface**: Geoptimaliseerd voor mobiele apparaten

### 👤 GENERAL_ACCESS
Basis toegang voor algemene gebruikers:
- **Alleen-lezen**: Orders bekijken zonder bewerkingsrechten
- **Beperkte filters**: Basis zoek- en filtermogelijkheden
- **Export functie**: Data export voor eigen gebruik
- **Profiel beheer**: Eigen gebruikersprofiel aanpassen

---

## 🧭 Navigatie & Interface

### Zijbalk (Sidebar) Navigatie
De hoofdnavigatie bevindt zich in de linker zijbalk en is volledig aanpasbaar:

#### **🏠 Dashboard**
- **Hoofdoverzicht**: Centrale orderweergave
- **Toegang**: Alle gebruikers
- **Functie**: Real-time overzicht van alle actieve orders
- **URL**: Direct naar orders-dashboard pagina

#### **📚 History**
- **Orderhistorie**: Voltooide en gearchiveerde orders
- **Toegang**: Alle gebruikers
- **Functies**: Zoeken in historische data, datum filters
- **Restauratie**: Beheerders kunnen orders terugzetten

#### **📊 Dashboard Pages (Uitklapbare Sectie)**
- **Type**: Aangepaste dashboard overzichten
- **Inhoud**: Door gebruikers gemaakte dashboards
- **Organisatie**: Automatisch gegroepeerd in sectie
- **Herordening**: Drag & drop volgorde aanpassing

#### **🔍 Scan Pages (Uitklapbare Sectie)**
- **Type**: Barcode scanning interfaces
- **Doel**: Productievloer scanning functionaliteit
- **Interface**: Geoptimaliseerd voor touch en snelle invoer
- **Integration**: Direct gekoppeld aan ordergegevens

#### **✏️ Edit Custom Pages**
- **Positie**: Vast onderaan sidebar
- **Toegang**: Alle gebruikers (functionaliteit rol-afhankelijk)
- **Functie**: Beheer van aangepaste pagina's
- **Beheer**: Maken, bewerken, archiveren van custom pages

### Sidebar Aanpassingen
- **Drag & Drop**: Volgorde van menu-items wijzigen
- **Sectie Inklapbaar**: Dashboard/Scan secties in-/uitklappen
- **Gebruikersspecifiek**: Elke gebruiker eigen sidebar configuratie
- **Automatisch bijwerken**: Nieuwe pagina's automatisch toegevoegd
- **Grip handvat**: Visuele indicatie voor versleepbare items

### Topbalk (Header) Functionaliteiten

#### **Paginatitel**
- **Dynamisch**: Past automatisch aan per pagina
- **Custom pages**: Toont three-letter ID of paginanaam
- **Consistency**: Uniforme weergave door hele systeem

#### **Three-Letter ID Editor** (View-template pagina's)
- **Functie**: Korte identificatie voor custom pages
- **Format**: Maximaal 3 karakters (letters/cijfers)
- **Opslag**: Direct opslaan bij wijziging
- **Toegang**: Alleen pagina-eigenaar of beheerder
- **Gebruik**: Snelle identificatie in overzichten

#### **Actie Iconen Balk**

**🆘 Help Knop**
- **Functie**: Link naar gebruikershandleiding
- **Target**: Nieuwe tab/venster
- **Conditie**: Alleen zichtbaar als HANDBOEK_URL ingesteld

**🔔 Notification Bell**
- **Badge**: Aantal ongelezen notificaties
- **Real-time**: Live updates van nieuwe berichten
- **Link**: Direct naar notifications pagina
- **Kleuring**: Rode badge bij nieuwe berichten

**⚙️ Settings Icon**
- **Functie**: Direct naar instellingen pagina
- **Toegang**: Alle gebruikers
- **Inhoud**: Profiel, permissions, gebruikersbeheer

#### **👤 User Profile Dropdown**
Uitgebreide gebruikersinformatie en acties:

**Profiel Header**
- **Avatar**: Profielfoto of initiaal
- **Naam**: Volledige gebruikersnaam
- **Rol**: Huidige gebruikersrol
- **Email**: Gebruikers emailadres
- **Status**: "Active now" indicator

**Menu Opties**
- **Account Settings**: Profiel en wachtwoord aanpassen
- **Admin Panel**: (Alleen voor BEHEERDER) Systeembeheer
- **Sign Out**: Veilig uitloggen

**Footer Informatie**
- **App naam**: "Plannify"
- **Versie**: Huidige systeemversie

---

## 📊 Dashboard - Orderoverzicht (Hoofdpagina)

Het centrale orderoverzicht is de belangrijkste interface van Plannify en biedt uitgebreide mogelijkheden voor orderbeheer.

### Zoek- en Filterbalk

#### **🔍 Zoekbalk**
- **Positie**: Linksboven in interface
- **Functie**: Tekst zoeken in alle zichtbare kolommen
- **Real-time**: Zoekresultaten tijdens typen
- **Wildcard**: Ondersteunt gedeeltelijke matches
- **Case-insensitive**: Hoofdletter onafhankelijk

#### **📋 Status Filter Dropdown**
Voorgedefinieerde status filters:
- **Alle Orders**: Toont alle niet-voltooide orders (standaard)
- **Pending**: Orders in wachtstand
- **In Progress**: Orders in bewerking
- **Completed**: Voltooide orders
- **Custom statussen**: Afhankelijk van configuratie

#### **📄 Items per Pagina**
- **Opties**: 10, 25, 50, 100 items per pagina
- **Standaard**: 10 items (gebruiker kan wijzigen)
- **Opslag**: Keuze wordt per gebruiker bewaard
- **Performance**: Hogere waarden voor sneller werken

#### **👁️ Column Visibility Button**
- **Icoon**: Oog symbool
- **Functie**: Kolommen tonen/verbergen selectie
- **Modal**: Opent kolomselectie venster
- **Persistentie**: Keuzes worden opgeslagen per gebruiker

#### **📤 Import Button**
- **Icoon**: Upload symbool
- **Functie**: Handmatige bestandsimport
- **Formaat**: .txt bestanden (pipe-delimited)
- **Interface**: Upload modal met voortgangsweergave

### Priority Orders Sectie

#### **🌟 Hoogprioriteit Weergave**
- **Positie**: Boven normale orders tabel
- **Markering**: Geel gemarkeerde orders
- **Toegang**: BEHEERDER en PLANNER kunnen instellen
- **Drag & Drop**: Prioriteitsvolgorde aanpassen
- **Inklapbaar**: Sectie kan worden ingeklapt voor ruimte

#### **Prioriteit Beheer**
- **Toevoegen**: Orders selecteren voor prioriteit
- **Verwijderen**: Prioriteit status weghalen
- **Herschikken**: Volgorde binnen prioriteiten wijzigen
- **Visuele feedback**: Directe bevestiging van wijzigingen

### Orders Tabel Interface

#### **📋 Tabelheader Functionaliteit**
- **Sorteerbaar**: Klik op elke kolomnaam voor sortering
- **Multi-sort**: Meerdere kolommen tegelijk sorteren
- **Sort indicatoren**: Pijltjes tonen sorteerrichting (↑↓)
- **Sticky header**: Header blijft zichtbaar bij scrollen
- **Responsive**: Past aan op verschillende schermgroottes

#### **🎛️ Column Header Opties**
- **Hover effecten**: Toon sort/filter opties bij mouse-over
- **Right-click menu**: Snelle kolom acties
- **Resize functie**: Kolombreedte aanpasbaar door slepen
- **Filter iconen**: Per kolom filter status indicator

#### **📝 Rij (Row) Functionaliteiten**
- **Hover highlight**: Rij markering bij mouse-over
- **Right-click menu**: Rij-specifieke context acties
- **Cell editing**: Dubbelklik voor directe cel bewerking
- **Row selection**: Checkbox voor bulk acties
- **Color coding**: Status-afhankelijke kleuring

#### **🖱️ Cell Editing Modal**
Geavanceerde cel bewerking voor precisie:

**Trigger Methods**
- **Dubbelklik**: Op bewerkbare cel
- **Enter toets**: Na cel selectie
- **Context menu**: Via right-click optie

**Modal Elementen**
- **Field label**: Duidelijke kolomnaam weergave
- **Input field**: Huidige waarde met formatting
- **Validation**: Real-time input controle
- **Save button**: Wijzigingen definitief maken
- **Cancel button**: Wijzigingen verwerpen

**Toegangscontrole**
- **Read-only cellen**: Grijs weergegeven
- **Permission-based**: Afhankelijk van gebruikersrol
- **Slotje protection**: Vergrendelde orders speciale behandeling
- **Field restrictions**: Bepaalde velden alleen voor specifieke rollen

### Order Management Modals

#### **➕ Add/Edit Order Modal**
Uitgebreide order invoer en bewerking:

**Trigger Methods**
- **"Add Order" knop**: Nieuwe order toevoegen
- **Edit actie**: Bestaande order wijzigen
- **Duplicate functie**: Order kopiëren

**Formulier Elementen**
- **Required fields**: Rode asterisk (*) markering
- **Validation**: Real-time feedback tijdens invoer
- **Date pickers**: Kalenderselectie voor data
- **Dropdowns**: Voorgedefinieerde waarden selectie
- **Auto-complete**: Intelligente suggesties

**Action Buttons**
- **Save**: Order opslaan en modal sluiten
- **Save & Add Another**: Opslaan en direct nieuwe order
- **Cancel**: Annuleren zonder wijzigingen opslaan
- **Delete**: Order verwijderen (alleen in edit modus)

#### **🔍 Order Details Modal**
Uitgebreide order informatie weergave:

**Trigger Methods**
- **Order ID klik**: Direct op order nummer
- **Detail knop**: Via tabel acties
- **Context menu**: Right-click optie

**Informatie Secties**
- **All fields**: Volledige order informatie overzicht
- **Timestamps**: Aanmaak en laatste wijziging datums
- **Change history**: Volledig wijzigingslogboek
- **Related data**: Gerelateerde orders en informatie
- **User actions**: Wie heeft wat wanneer gewijzigd

**Available Actions**
- **Edit**: Direct naar edit modal
- **Duplicate**: Order kopiëren naar nieuwe
- **Export**: Order data exporteren
- **Print**: Printbare versie

### Pagination & Navigatie

#### **📖 Pagination Controls**
- **Positie**: Onderaan tabel
- **Info display**: "Showing X to Y of Z entries"
- **Navigatie opties**: Eerste, Vorige, Pagina nummers, Volgende, Laatste
- **Direct navigation**: Input veld voor directe pagina sprong
- **Keyboard navigation**: Pijltjestoetsen ondersteuning

#### **Performance Optimalisatie**
- **Lazy loading**: Alleen zichtbare data laden
- **Caching**: Veel gebruikte data cachen
- **Progressive loading**: Grote datasets gefaseerd laden

---

## 📚 Order Historie Pagina

Uitgebreide geschiedenis en archief functionaliteit.

### Historie Interface

#### **📊 Completed Orders Weergave**
- **Filter**: Alleen orders met "Completed" status
- **Tijdsbereik**: Configureerbare datum range
- **Zoekfunctie**: Volledige tekst zoek in historie
- **Performance**: Geoptimaliseerd voor grote datasets

#### **🔍 Archive Search**
- **Geavanceerd zoeken**: Specifieke velden doorzoeken
- **Datum filters**: Van/tot datum selectie
- **Status historie**: Zoeken op historische statusen
- **User filters**: Zoeken op wie wijzigingen heeft gemaakt

#### **📈 Analytics & Reporting**
- **Completion trends**: Order voltooiing statistieken
- **Performance metrics**: Doorlooptijd analyses
- **User activity**: Wie heeft wat gedaan
- **Export opties**: Data export voor externe analyse

### Historie Beheer

#### **♻️ Restore Functionaliteit** (Alleen BEHEERDER)
- **Order selectie**: Specifieke orders selecteren
- **Bulk restore**: Meerdere orders tegelijk
- **Status reset**: Orders terugzetten naar actieve status
- **Logging**: Volledige audit trail van restore acties

#### **🗂️ Archive Management**
- **Automatic archiving**: Oude orders automatisch archiveren
- **Manual archiving**: Handmatige archivering opties
- **Archive policies**: Configureerbare archivering regels
- **Storage optimization**: Efficiënte data opslag

---

## 🎛️ Aangepaste Pagina's (Custom Pages)

Krachtige functionaliteit voor het maken van departement-specifieke dashboards.

### Page Templates Beheer

#### **🏗️ Custom Pages Overzicht**
**Hoofdinterface elementen:**
- **Active Pages List**: Overzicht van alle actieve custom pages
- **Archived Pages**: Gearchiveerde pagina's (alleen BEHEERDER toegang)
- **Create Page Button**: Nieuwe pagina maken functionaliteit
- **Search functie**: Zoeken in pagina namen en beschrijvingen

#### **📋 Custom Pages Tabel**
**Kolom informatie:**
- **Page Name**: Unieke naam van de aangepaste pagina
- **Type**: Dashboard of Scan type indicator
- **Columns**: Aantal kolommen (eerste 3 getoond in preview)
- **Created By**: Gebruiker die de pagina heeft gemaakt
- **Last Updated**: Laatste wijzigingsdatum
- **Actions**: Beschikbare acties (View, Edit, Archive)

**Type Indicators:**
- **📊 Dashboard**: Tabel icoon voor overzichtspagina's
- **🔍 Scan**: Barcode icoon voor scanning interfaces

#### **➕ Page Creation Modal**
**Formulier velden:**
- **Page Name**: Unieke paginanaam (verplicht veld)
- **Page Type Selection**: Dashboard of Scan type keuze

**Type beschrijvingen:**
- **Dashboard**: "Voor overzicht displays en verschijnen bovenaan in sidebar menu"
- **Scan**: "Voor barcode scanning functionaliteit op productievloer"

**Automatische configuratie:**
- **Auto-include**: Alle Order tabel kolommen automatisch beschikbaar
- **No manual selection**: Geen handmatige kolomselectie nodig
- **Smart defaults**: Intelligente standaard instellingen

**Action buttons:**
- **Cancel**: Annuleren zonder opslaan
- **Save Page**: Pagina opslaan en beschikbaar maken

#### **📦 Archive/Restore Modals**
**Archive functionaliteit:**
- **Confirmation modal**: Bevestiging voor archivering
- **Impact warning**: Waarschuwing over gevolgen
- **User notification**: Automatische melding aan gebruikers

**Restore opties:**
- **Archive overzicht**: Lijst van gearchiveerde pagina's
- **Restore confirmation**: Bevestiging voor herstel
- **Conflict detection**: Detectie van naam conflicten

### View Template Functionaliteit

#### **🖥️ Custom Page Viewer**
**URL structuur:** `?page=view-template&id=[page_id]`

**Interface elementen:**
- **Three-Letter ID Editor**: In topbalk voor snelle identificatie
- **Full Order Display**: Alle kolommen van Order tabel beschikbaar
- **Custom filtering**: Pagina-specifieke filter opties
- **Real-time updates**: Live data synchronisatie

#### **🎨 Customization Opties**
- **Column visibility**: Gebruiker kan kolommen tonen/verbergen
- **Column ordering**: Drag & drop kolom herrangschikking
- **Filter presets**: Vooraf ingestelde filter combinaties
- **View modes**: Verschillende weergave modi

#### **🔄 Scan Integration** (Voor scan-type pagina's)
- **Barcode input**: Geoptimaliseerde barcode invoer
- **Scan historie**: Scan activiteit tracking
- **Status updates**: Real-time status wijzigingen
- **Audio feedback**: Geluid bevestiging van scans

---

## 🔍 Scan Functionaliteit

Geavanceerde barcode scanning voor productietracking.

### Scan Interface Elementen

#### **📷 Barcode Scanner Input**
**Technische features:**
- **Auto-focus**: Automatische focus voor hardware scanners
- **Real-time processing**: Directe verwerking van gescande codes
- **Multiple formats**: Ondersteuning voor verschillende barcode types
- **Error detection**: Automatische detectie van scan fouten

**User experience:**
- **Sound feedback**: Audio bevestiging van succesvolle scans
- **Visual feedback**: Kleur en animatie indicaties
- **Keyboard shortcuts**: Sneltoetsen voor efficiency
- **Touch optimization**: Geoptimaliseerd voor touch screens

#### **📊 Scan History Sidebar**
**Historie weergave:**
- **Recent scans**: Chronologisch overzicht van laatste scans
- **Timestamp**: Precieze tijd van elke scan
- **User info**: Identificatie van scanning gebruiker
- **Status indicator**: Succes/fout status per scan
- **Order linking**: Directe link naar gerelateerde orders

#### **🚦 Traffic Light System**
**Status indicatie systeem:**
- **🔴 Rood**: Fout of probleem gedetecteerd
- **🟡 Geel**: Waarschuwing of wachten op verwerking
- **🟢 Groen**: Succesvol verwerkt
- **🔵 Blauw**: Informatief bericht
- **⚫ Grijs**: Geen status/neutraal

### Scan Workflow Process

#### **📋 Scan Proces Stappen**
1. **Page Access**: Navigatie naar scan-type pagina
2. **Scanner Ready**: Interface toont scanner gereed status
3. **Barcode Scan**: Fysieke scan van product barcode
4. **Code Processing**: Systeem verwerkt en valideert code
5. **Order Lookup**: Automatische order opzoek functie
6. **Status Update**: Order status bijwerken indien nodig
7. **Feedback Display**: Visuele/audio bevestiging aan gebruiker
8. **History Logging**: Scan toevoegen aan gebruiker historie

#### **💾 Scan Data Storage**
**Database tracking:**
- **scan_history tabel**: Centrale opslag van alle scans
- **Page ID**: Welke pagina gebruikt voor scan
- **Order number**: Gescand ordernummer
- **Plate code**: Exacte barcode waarde
- **Scanned by**: Gebruiker identificatie
- **Scan timestamp**: Precieze tijd van scan
- **Scan type**: Categorisatie van scan type
- **Notes field**: Extra opmerkingen of context

### Fullscreen Scan Interface

#### **🖥️ Productievloer Optimalisatie**
**Interface aanpassingen:**
- **Large touch targets**: Grote knoppen voor handschoenen
- **High contrast**: Goed zichtbaar in productie omgeving
- **Minimal distractions**: Alleen essentiële informatie
- **Auto-hide controls**: Automatisch verbergen van menu's
- **Voice feedback**: Gesproken bevestigingen

**Performance optimalisatie:**
- **Fast response**: Snelle reactietijd voor efficiency
- **Offline capability**: Beperkte offline functionaliteit
- **Battery optimization**: Energiezuinig voor mobiele apparaten

---

## ⚙️ Instellingen & Configuratie

Uitgebreide configuratiemogelijkheden voor gebruikers en beheerders.

### Settings Tabs Overzicht

#### **👤 Profile & Password Tab** (Alle gebruikers)
**Profiel management:**
- **Persoonlijke gegevens**: Naam, email, telefoon
- **Profielfoto**: Upload en crop functionaliteit
- **Wachtwoord wijziging**: Veilige wachtwoord update
- **Interface voorkeuren**: Taal, tijdzone, weergave opties
- **Notification settings**: Email en browser notificatie voorkeuren

**Veiligheidsfeatures:**
- **Current password verification**: Huidige wachtwoord bevestiging
- **Password strength meter**: Wachtwoord sterkte indicator
- **Two-factor authentication**: Optionele 2FA setup
- **Login history**: Recente login activiteit

#### **🔑 Column Permissions Tab** (Alleen BEHEERDER)
**Rechten configuratie:**
- **Per-column permissions**: Toegangsrechten per tabel kolom
- **Role-based access**: Rechten per gebruikersrol
- **Read/Write/Hidden**: Drie toegangsniveaus per kolom
- **Bulk operations**: Massa wijziging van rechten
- **Permission templates**: Vooraf gedefinieerde rechten sets

**Advanced features:**
- **Conditional permissions**: Rechten gebaseerd op order status
- **Time-based access**: Tijdelijke toegangsrechten
- **Field-level security**: Specifieke velden beveiligen
- **Audit logging**: Logging van rechten wijzigingen

#### **👥 Account Management Tab** (Alleen BEHEERDER)
**User Management Sectie:**

**User Overview Tabs:**
- **Active Users**: Huidige actieve gebruikers
- **Inactive Users**: Gedeactiveerde accounts
- **Pending Users**: Accounts in afwachting van activering
- **Admin Users**: Overzicht van beheerders

**Add User Form:**
- **Basic information**: Naam, email, telefoon
- **Role assignment**: Gebruikersrol selectie
- **Initial password**: Tijdelijk wachtwoord setup
- **Activation method**: Email of handmatige activering
- **Department assignment**: Afdeling toewijzing

**User Table Informatie:**
- **User column**: Naam en email adres
- **Role column**: Badge met rol en kleurcodering
- **Created column**: Account aanmaakdatum
- **Last Login**: Laatste inlog timestamp
- **Status column**: Actief/Inactief status indicator
- **Actions column**: Bewerken, Deactiveren, Verwijderen

**User Actions:**
- **Edit User**: Gebruikersgegevens wijzigen
- **Reset Password**: Wachtwoord reset forceren
- **Change Role**: Gebruikersrol aanpassen
- **Deactivate Account**: Account tijdelijk uitschakelen
- **Delete User**: Permanente account verwijdering (met bevestiging)

### Systeem Configuratie

#### **🔧 System Settings** (Alleen BEHEERDER)
**Algemene instellingen:**
- **Application name**: Systeem naam aanpassing
- **Default language**: Standaard taal instelling
- **Timezone settings**: Tijdzone configuratie
- **Date format**: Datum weergave formaat
- **Session timeout**: Automatische uitlog tijd

**Performance instellingen:**
- **Cache settings**: Cache configuratie
- **Database optimization**: Database performance instellingen
- **File upload limits**: Maximum bestandsgrootte
- **Backup scheduling**: Automatische backup planning

#### **📧 Notification Configuration**
**Email instellingen:**
- **SMTP configuration**: Email server instellingen
- **Email templates**: Aangepaste email templates
- **Delivery settings**: Bezorg opties en timing
- **Bounce handling**: Afgeketste email verwerking

**Browser notificaties:**
- **Push notifications**: Browser push berichten
- **Real-time updates**: Live notificatie updates
- **Sound settings**: Audio notificatie instellingen
- **Display duration**: Hoe lang notificaties zichtbaar blijven

---

## 🔔 Notificaties Systeem

Uitgebreid communicatiesysteem voor gebruikers en beheerders.

### Notification Types

#### **📤 Import Notifications**
**Automatische import berichten:**
- **Success notifications**: Succesvolle import statistieken
- **Failure alerts**: Foutmeldingen met details
- **Processing updates**: Voortgang van grote imports
- **Statistics summary**: Aantal nieuwe, bijgewerkte, overgeslagen orders
- **File information**: Bestandsnaam en verwerkingstijd

**Recipients en timing:**
- **All users**: Alle gebruikers ontvangen import updates
- **Auto-clear**: Berichten verdwijnen na gelezen
- **Frequency control**: Niet te veel berichten per tijdsperiode

#### **🔒 Locked Order Notifications**
**Order vergrendeling berichten:**
- **Lock notifications**: Wanneer orders vergrendeld worden
- **Change alerts**: Wijzigingen aan vergrendelde orders
- **Unlock notifications**: Wanneer vergrendelingen opgeheven worden
- **Override alerts**: Wanneer beheerders vergrendelingen overschrijven

**Target audience:**
- **BEHEERDER en PLANNER**: Primaire ontvangers
- **Order owners**: Gebruikers die orders hebben vergrendeld
- **Action required**: Soms goedkeuring wijzigingen nodig

#### **⚠️ System Notifications**
**Systeem gebeurtenissen:**
- **Maintenance alerts**: Onderhoudsmeldingen en downtimes
- **Update notifications**: Systeem update informatie
- **Security alerts**: Beveiligings gerelateerde berichten
- **Performance warnings**: Prestatie gerelateerde waarschuwingen

**Priority levels:**
- **High priority**: Kritieke systeemberichten
- **Medium priority**: Belangrijke informatie
- **Low priority**: Algemene informatieve berichten

#### **👤 User Notifications**
**Gebruiker-specifieke berichten:**
- **Account changes**: Wijzigingen aan account instellingen
- **Permission updates**: Rechten wijzigingen
- **Login alerts**: Verdachte login activiteit
- **Password reminders**: Wachtwoord vervaldatum herinneringen

### Notification Interface

#### **🔔 Notification Bell**
**Header notification systeem:**
- **Badge counter**: Aantal ongelezen berichten
- **Real-time updates**: Live badge updates
- **Visual indicators**: Kleurcodering voor urgentie
- **Click action**: Direct naar notifications pagina

#### **📱 Notifications Page**
**Uitgebreide notification management:**
- **Message history**: Chronologisch overzicht van alle berichten
- **Filter options**: Filter op type, datum, gelezen status
- **Mark actions**: Mark as read/unread functionaliteit
- **Bulk operations**: Massa acties op berichten
- **Search functionality**: Zoeken in notification historie

**Message details:**
- **Timestamp**: Exacte tijd van bericht
- **Sender**: Van wie het bericht komt
- **Type indicator**: Visuele type identificatie
- **Priority**: Urgentie niveau weergave
- **Action buttons**: Relevante acties per bericht

#### **🔄 Real-time Updates**
**Live notification system:**
- **WebSocket connection**: Real-time verbinding voor updates
- **Auto-refresh**: Automatische pagina verversing
- **Sound alerts**: Audio signalen voor nieuwe berichten
- **Desktop notifications**: Browser desktop berichten

---

## 📥 Import Systeem

Geavanceerd automatisch import systeem voor orderbestanden.

### Import Architectuur

#### **🔄 Dual Import System**
**Twee parallelle import mechanismen:**

**1. Dedicated Import Service Container**
- **Aparte Docker container**: Onafhankelijke import service
- **Continuous monitoring**: 24/7 directory monitoring
- **60-second intervals**: Controle elke minuut
- **Persistent process**: Altijd actieve achtergrondservice
- **Resource optimization**: Dedicated resources voor import

**2. Web Container Cron Import**
- **Web applicatie container**: Via hoofdcontainer
- **Cron job scheduling**: Minutelijks via crontab
- **Backup mechanism**: Redundantie voor betrouwbaarheid
- **Same logic**: Identieke verwerkingslogica
- **Failover capability**: Automatische overname bij problemen

### Import Triggers

#### **🕐 Automatic Time-based**
**Scheduling mechanismen:**
- **Import service**: Continue 60-seconden loop
- **Web cron**: Elke minuut uitvoering
- **24/7 monitoring**: Ononderbroken bestandscontrole
- **No intervention**: Geen handmatige actie nodig

#### **📁 File-based Triggers**
**Bestand detectie:**
- **Directory monitoring**: Specifieke mappen worden gemonitord
- **Immediate detection**: Binnen 60 seconden detectie
- **Multiple files**: Sequentiële verwerking van meerdere bestanden
- **File validation**: Controle op juiste format en inhoud

#### **👤 Manual Import**
**Handmatige triggers:**
- **Dashboard UI**: Import knop in interface
- **File upload**: Direct upload via browser
- **Immediate processing**: Directe verwerking
- **User feedback**: Real-time voortgang weergave

### Import Directories

#### **📂 Import Service Paths**
**Dedicated container directories:**
- **Incoming**: `/opt/import_files/incoming/` - Nieuwe bestanden
- **Processed**: `/opt/import_files/processed/` - Succesvol verwerkt
- **Failed**: `/opt/import_files/failed/` - Gefaalde verwerkingen

#### **🌐 Web Container Paths**
**Web applicatie directories:**
- **Incoming**: `/var/www/html/uploads/import/` - Upload directory
- **Processed**: `/var/www/html/uploads/processed/` - Verwerkte bestanden
- **Failed**: `/var/www/html/uploads/failed/` - Foutieve bestanden

### Import Process Flow

#### **🔍 File Discovery & Validation**
**Detectie proces:**
1. **Directory scanning**: Regelmatige controle van incoming folders
2. **File extension check**: Alleen .txt bestanden verwerken
3. **File readability**: Controle of bestand leesbaar is
4. **Encoding detection**: Automatische encoding detectie
5. **Minimum validation**: Controle op minimum aantal kolommen

#### **⚙️ Data Processing**
**Verwerkings stappen:**
1. **Header parsing**: Lezen en interpreteren van header rij
2. **Column mapping**: Mapping van kolommen naar database velden
3. **Data transformation**: Formattering van data (datums, getallen)
4. **Validation**: Controle op data integriteit
5. **Duplicate detection**: Detectie van bestaande orders

#### **💾 Database Operations**
**Database interacties:**
1. **Transaction start**: Begin database transactie
2. **INSERT/UPDATE logic**: `INSERT ... ON DUPLICATE KEY UPDATE`
3. **Existing record updates**: Bijwerken van bestaande orders
4. **New record insertion**: Toevoegen van nieuwe orders
5. **Transaction commit**: Definitief maken van wijzigingen

#### **📊 Post-Processing**
**Na verwerking:**
1. **File management**: Verplaatsen naar processed/failed directory
2. **Timestamp addition**: Timestamp toevoegen aan bestandsnaam
3. **Notification creation**: Gebruikersberichten aanmaken
4. **Log updating**: Import log bijwerken
5. **Statistics tracking**: Verwerking statistieken bijhouden

### Import Monitoring

#### **📊 Log Locations**
**Import Service logs:**
- **Main log**: `/var/log/import_service/import.log`
- **Error log**: `/var/log/import_service/import_errors.log`
- **Real-time monitoring**: `docker compose exec import-service tail -f [log]`

**Web Container logs:**
- **Main log**: `/var/www/html/api/dashboard/import_cron.log`
- **Error log**: `/var/www/html/api/dashboard/import_automation.log`
- **Real-time monitoring**: `docker compose exec web tail -f [log]`

#### **📈 Import Statistics**
**Verwerking metrics:**
- **Processed count**: Totaal aantal verwerkte orders
- **Imported count**: Aantal nieuwe orders toegevoegd
- **Updated count**: Aantal bijgewerkte bestaande orders
- **Skipped count**: Aantal ongewijzigde orders
- **Error count**: Aantal records met fouten
- **Processing time**: Verwerkingstijd per bestand

### Troubleshooting

#### **❗ Veelvoorkomende Problemen**
**File processing issues:**
- **Encoding problemen**: Automatische UTF-8 conversie
- **Delimiter fouten**: Controleer pipe (|) delimiter
- **Permission issues**: Bestands rechten controle
- **Large file handling**: Speciale behandeling grote bestanden

**Database problemen:**
- **Connection errors**: Database connectiviteit
- **Lock conflicts**: Gelijktijdige toegang problemen
- **Memory issues**: Geheugen tekort bij grote imports
- **Performance optimization**: Database index optimalisatie

---

## 🔧 Utilities & Maintenance Tools

Uitgebreide set hulpmiddelen voor systeembeheer en onderhoud.

### Maintenance Scripts

#### **🔧 Database Maintenance**
**Database optimalisatie tools:**
- **Index optimization**: Database index beheer
- **Table cleanup**: Opruimen van oude data
- **Performance monitoring**: Query performance tracking
- **Backup utilities**: Automatische backup functionaliteit

#### **👤 User Management Tools**
**Gebruiker beheer scripts:**
- **Account cleanup**: Opruimen van oude accounts
- **Permission sync**: Synchronisatie van rechten
- **Profile validation**: Validatie van gebruikersprofielen
- **Access audit**: Audit van toegangsrechten

#### **📊 System Monitoring**
**Systeem monitoring tools:**
- **Resource usage**: CPU, memory, disk monitoring
- **Performance metrics**: Response tijd tracking
- **Error logging**: Centralized error tracking
- **Health checks**: Automatische systeem health checks

#### **🔄 Migration Scripts**
**Database en systeem migraties:**
- **Schema updates**: Database schema wijzigingen
- **Data migrations**: Data transformatie scripts
- **Version upgrades**: Systeem upgrade scripts
- **Rollback procedures**: Terugrol mechanismen

### Configuration Management

#### **⚙️ Environment Configuration**
**Omgeving instellingen:**
- **Docker configuration**: Container configuratie
- **Database settings**: Database verbinding instellingen
- **Security settings**: Beveiligings configuratie
- **Performance tuning**: Performance optimalisatie

#### **📁 File Management**
**Bestandsbeheer tools:**
- **Log rotation**: Automatische log rotatie
- **Backup management**: Backup beheer
- **Archive utilities**: Archivering functies
- **Cleanup scripts**: Automatische opruiming

---

## 🎨 Interface & User Experience

### Responsive Design

#### **📱 Mobile Optimization**
**Mobile interface aanpassingen:**
- **Touch-friendly buttons**: Grote knoppen voor touch screens
- **Swipe gestures**: Swipe navigatie ondersteuning
- **Auto-zoom prevention**: Voorkomen van ongewenste zoom
- **Mobile-first design**: Primair ontworpen voor mobiel

#### **💻 Desktop Enhancement**
**Desktop specifieke functies:**
- **Keyboard shortcuts**: Sneltoetsen voor power users
- **Multi-window support**: Meerdere vensters ondersteuning
- **Hover effects**: Mouse-over effecten
- **Right-click menus**: Context menu's

#### **📺 Large Display Support**
**Grote schermen optimalisatie:**
- **Fullscreen modes**: Volledig scherm weergave
- **High resolution**: 4K en hoger resolutie ondersteuning
- **Distance viewing**: Optimalisatie voor afstand bekijken
- **Production floor**: Speciale productievloer modi

### Accessibility Features

#### **♿ Accessibility Compliance**
**Toegankelijkheids functies:**
- **Screen reader support**: Ondersteuning voor schermlezer software
- **Keyboard navigation**: Volledige keyboard bediening
- **High contrast modes**: Hoge contrast weergave opties
- **Font size scaling**: Aanpasbare lettergrootte

#### **🌐 Multi-language Support**
**Meertalige ondersteuning:**
- **Dutch primary**: Nederlands als primaire taal
- **English support**: Engelse interface optie
- **Date formatting**: Lokale datum formaten
- **Number formatting**: Lokale cijfer formaten

### Performance Optimization

#### **⚡ Speed Enhancements**
**Performance verbeteringen:**
- **Lazy loading**: Alleen zichtbare content laden
- **Caching strategies**: Intelligente cache mechanismen
- **Progressive loading**: Gefaseerd laden van data
- **Compression**: Data compressie voor snellere overdracht

#### **🔄 Real-time Updates**
**Live data synchronisatie:**
- **WebSocket connections**: Real-time data verbindingen
- **Auto-refresh**: Automatische pagina verversing
- **Conflict resolution**: Automatische conflict oplossing
- **Optimistic updates**: Optimistische UI updates

---

## 🔒 Security & Privacy

### Data Protection

#### **🛡️ Data Security**
**Data bescherming maatregelen:**
- **Encryption**: Data encryptie in rust en transport
- **Access logging**: Volledige toegang logging
- **Audit trails**: Complete audit geschiedenis
- **Data anonymization**: Anonimisering voor privacy

#### **🔐 User Authentication**
**Gebruiker authenticatie:**
- **Secure passwords**: Veilige wachtwoord eisen
- **Session management**: Veilige sessie beheer
- **Brute force protection**: Bescherming tegen brute force aanvallen
- **Account lockout**: Automatische account vergrendeling

### Compliance & Auditing

#### **📋 Compliance Features**
**Compliance ondersteuning:**
- **GDPR compliance**: AVG/GDPR naleving
- **Data retention**: Data bewaar beleid
- **Privacy controls**: Privacy instellingen
- **Consent management**: Toestemming beheer

#### **🔍 Audit Capabilities**
**Audit functionaliteit:**
- **User activity tracking**: Gebruiker activiteit tracking
- **Change logging**: Volledige wijziging logging
- **System events**: Systeem gebeurtenissen logging
- **Report generation**: Automatische rapport generatie

---

## 📞 Support & Help

### Documentation

#### **📚 User Guides**
**Gebruikers documentatie:**
- **Complete handbook**: Volledige gebruikershandleiding
- **Quick start guide**: Snelle start gids
- **Feature tutorials**: Functie specifieke tutorials
- **Video guides**: Video instructies

#### **🔧 Technical Documentation**
**Technische documentatie:**
- **API documentation**: API referentie
- **Database schema**: Database structuur documentatie
- **Configuration guides**: Configuratie handleidingen
- **Troubleshooting**: Probleemoplossings gidsen

### Getting Help

#### **❓ Built-in Help**
**Ingebouwde hulp:**
- **Context-sensitive help**: Context gevoelige hulp
- **Tooltips**: Informatieve tooltips
- **Help buttons**: Hulp knoppen door interface
- **Interactive tutorials**: Interactieve tutorials

#### **🆘 Support Channels**
**Ondersteuning kanalen:**
- **Admin contact**: Direct contact met beheerders
- **Documentation links**: Links naar documentatie
- **FAQ sections**: Veelgestelde vragen
- **Community support**: Gebruiker gemeenschap

---

**🎯 Dit document bevat alle functionaliteit van het Plannify systeem. Voor technische implementatie details, zie het separate bestandsstructuur document.**
