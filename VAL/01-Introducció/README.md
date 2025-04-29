# 01 - Introducció

Benvingut al curs de **PartyRock**!

En este curs, aprendràs a crear **aplicacions d'IA generativa** sense escriure una sola línia de codi, utilitzant PartyRock i el poder dels models fundacionals en Amazon Bedrock.

---

## 🚀 Què és PartyRock?

**PartyRock** és una plataforma sense codi desenvolupada per AWS que permet als usuaris crear i personalitzar aplicacions d'IA generativa de forma ràpida i senzilla.  
Aprofita els models fundacionals (FMs) a través d'**Amazon Bedrock** per a generar textos, imatges i altres mitjans basats en prompts de l'usuari.

PartyRock és ideal per a:
- Prototipat ràpid
- Aprenentatge sobre IA
- Creació de demos
- Hackathons i esdeveniments d'innovació

---

## 📚 Què aprendràs?

Al llarg d'este curs:

- Comprendràs els conceptes bàsics de la **IA Generativa**.
- Exploraràs les capacitats de **PartyRock**.
- Construiràs la teua **primera aplicació d'IA**.
- Aprendràs a **desplegar** i **compartir** les teues aplicacions.
- Descobriràs **millors pràctiques** al dissenyar aplicacions amb IA generativa.
- Participaràs en un **projecte estil hackathon** per a consolidar el teu aprenentatge.

---

## 👤 Per a qui és este curs?

Este curs està dirigit a:

- Principiants interessats en la Intel·ligència Artificial.
- Desenvolupadors que volen prototipar idees d'IA ràpidament.
- Educadors i estudiants que exploren aplicacions d'IA.
- Innovadors que participen en hackathons.
- Qualsevol persona curiosa sobre plataformes sense codi i IA generativa.

---

## 🛠️ Requisits previs

No es requereixen coneixements previs de programació!

Només necessites:

- Un compte gratuït de PartyRock.
- Curiositat i creativitat.

---

## 📂 Material de suport

En cada mòdul, trobaràs:
- Text explicatiu
- Exercicis pas a pas
- Diagrames i imatges
- Projectes d'exemple

Les imatges estaran ubicades en la carpeta [`images/`](./images) per a referència.

---

## 🎯 Comencem!

![Imatge de benvinguda](./images/welcome-partyrock.png)

---

## 1 · Explorant la interfície de PartyRock

En quant inicies sessió, PartyRock et dona la benvinguda amb un espai de treball brillant i minimalista:

![Pantalla d'inici](./images/00_partyrock-home.png)

*La barra lateral esquerra és el teu panell de control; l'ampli llenç de la dreta és on pren forma cada aplicació.*

---

### 1.1 Genera la teua primera aplicació

Selecciona **Generar aplicació** i se t'oferiran dos camins:

1. **Descriu una idea** en llenguatge comú (PartyRock crea l'estructura de l'aplicació per tu).  
2. **Construïx manualment** des d'un llenç buit.

![Diàleg de generació d'aplicació](./images/01_partyrock-generate-app-prompt.png)

Si tries l'"Aplicació en blanc", seràs rebut pel llenç buit de PartyRock, preparat perquè comences a construir:

![Llenç en blanc](./images/02_partyrock-empty-app.png)

---

### 1.2 Vista del repositori

Cada aplicació que crees apareix en el teu repositori personal.  
Ací pots crear **instantànies**, **duplicar** o **publicar** qualsevol projecte.

![Repositori d'aplicacions](./images/03-repo-apps.png)

Les instantànies són invaluables per al control de versions:

![Panell d'instantànies](./images/04-snapshots-partyrock.png)  

Pots crear una instantània en qualsevol moment, la qual cosa et permet tornar a un estat anterior de la teua aplicació.
Açò és especialment útil si experimentes amb diferents configuracions o models i vols tornar a una versió anterior.
Pots veure l'historial d'instantànies i restaurar qualsevol versió anterior.


![Instantània activada](./images/05-partyrock-snapshots.png)

---

## 2 · Widgets – Els components bàsics

Obri l'editor i observa la **paleta de widgets**:
![Widget d'arxiu](./images/13_widget_file.png) 


| Categoria | Widgets típics | Exemple de captura de pantalla |
|----------|-----------------|--------------------|
| **Entrades** | Text · Selecció · Lliscador · Arxius |![Paleta de widgets](./images/12-createapp-widgets.png) |
| **Amb IA integrada** | Text generat · Imatge generada · Xat | ![Widget de text generat](./images/14-widget-iageneration.png) |
| **Altres** | Text estàtic per a capçaleres/instruccions | — |

---

### 2.1 Configuració del prompt

Cada widget d'IA inclou una pestanya de **Prompt**.  
Fes referència a altres widgets amb `@NomDelWidget`.

![Editor de prompt](./images/15-prompt-widgetgeneration.png)

---

## 3 · Triant un model fundacional

Canvia a la pestanya **Model** per a triar un model allotjat per Amazon Bedrock.

![Selector de model](./images/16-widget-modlepicker.png)


# 📊 Taula Comparativa de Models en PartyRock

| Model | Proveïdor | Descripció breu | Casos d'Ús principals |
|:------|:-----------|:-------------------|:-------------------------|
| **Claude 3.5 Haiku** | Anthropic | Molt ràpid, ideal per a apps en temps real | Desenvolupament àgil, chatbots, extracció de dades |
| **Claude 3.5 Sonnet v2** | Anthropic | Model insígnia, raonament avançat, multimodal | Desenvolupament full-stack, investigació, sistemes de diàleg |
| **Jamba 1.5 Large** | HuggingFace | Processament de llenguatge natural d'alta escala | Anàlisi semàntic, generació de contingut |
| **Jamba 1.5 Mini** | HuggingFace | Compacte i eficient per a recursos limitats | Aplicacions mòbils, processament bàsic |
| **Command R** | Cohere | Especialitzat en processament d'instruccions | Automatització, control de sistemes |
| **Command R+** | Cohere | Millor maneig d'instruccions complexes | Integracions avançades, RAG |
| **Amazon Nova Micro** | AWS | Ultra lleuger, ideal per a edge computing | IoT, sistemes embeguts, apps mòbils |
| **Amazon Nova Lite** | AWS | Balancejat per a cloud i web apps | Servicis en el núvol, apps web |
| **Amazon Nova Pro** | AWS | Alt rendiment, solucions empresarials | Anàlisi avançat, processament intensiu |
| **Llama 3.1 Instruct 70B** | Meta | Model de gran grandària per a tasques tècniques | Desenvolupament de programari, anàlisi tècnic |
| **Llama 3.1 Instruct 8B** | Meta | Versió lleugera de 8B paràmetres | Prototipat ràpid, tasques bàsiques |
| **Mistral Large 2 (24.07)** | Mistral AI | Multilingüe, generació de contingut professional | Anàlisi semàntic, NLP avançat |
| **Mistral Small 2 (24.02)** | Mistral AI | Compacte per a processament simple de text | Chatbots bàsics, apps lleugeres |

---


Ajusta la generació amb els lliscadors de **Temperatura** i **Top-P**:

![Paràmetres del model](./images/17-model-params.png)

| Ajust | Què fa | Regla ràpida |
|---------|--------------|------------|
| **Temperatura** | Afig **picant**. 0 = directe, 1 = creatiu. | Més baixa per a fets, més alta per a idees. |
| **Top-P** | Manté només el **P%** superior de paraules probables. | 0.5 = més segur, 1.0 = sense restriccions. |

**Exemple ("Escriu un tweet per a un dia plujós"):**

| Temp / Top-P | Possible resultat |
|--------------|-----------------|
| 0.2 / 1.0 | *"Plovisna, te, safata d'entrada tranquil·la. Perfecte."* |
| 0.7 / 0.9 | *"Londres goteja somnis d'espresso sobre la meua finestra."* |
| 0.9 / 1.0 | *"Els núvols fan poesia slam; els bassals responen en rima."* |

**Guia ràpida de casos d'ús**

- **Resum precís** → Temp 0.2 , Top-P 0.6  
- **Text per a blog** → Temp 0.5 , Top-P 0.9  
- **Idees boges** → Temp 0.9 , Top-P 1.0

![Resum de temperatura](./images/sampling-icecream-example.png)
---

## 4 · Generació d'imatges

Afig un widget d'*Imatge generada* per a convertir prompts de text en elements visuals:

![Generar imatges](./images/06-image-generation.png)

---

## 5 · Panells d'aprenentatge i suport

### 5.1 Guia de PartyRock

Manual pas a pas que cobreix com començar, construir i preguntes freqüents.

![Guia](./images/08-partyrock-guide.png)

### 5.2 Novetats

Notes de llançament i destacats de noves funcions.

![Novetats](./images/09-partyrock-whatsnew.png)

### 5.3 Full de ruta pública

Vota per futures funcions o envia les teues pròpies sol·licituds.

![Full de ruta](./images/10-partyrock-roadmap.png)

### 5.4 Backstage

Un panell que agrega mòduls d'aprenentatge, instantànies i estadístiques d'ús.

![Backstage](./images/11-partyrock-backstage.png)

---

## 6 · Mini tutorial — D'un llenç en blanc a una aplicació funcional

1. **Crea** una aplicació en blanc.  
2. Afig el widget **Arxius** `Currículum` i el widget **Text** `Oferta de treball`.  
3. Afig el widget **Text generat** `Avaluació`.  
4. En Prompt, compara `@Currículum` amb `@Oferta de treball` i mostra una puntuació de coincidència.  
5. Selecciona **Amazon Nova Pro**, Temperatura 0.4.  
6. Crea una instantània, itera i després publica.

Acabes de crear un analitzador funcional de CV i ofertes de treball sense escriure una sola línia de codi!

---

## 7 · Següents passos suggerits

- Modifica l'exemple per a traduir correus electrònics o generar cartes de presentació.  
- Alterna entre **Claude Sonnet** i **Llama 70 B** per a observar diferències estilístiques.  
- Explora widgets d'imatges per a aplicacions creatives com generadors de logos o creadors de tires còmiques.

---

### 🎉 Benvingut de nou a PartyRock – gaudix construint! 🚀

---

## 📚 Continua el curs

**[➡️ Següent mòdul: 02 - Construint La Teua Primera Aplicació](../02-Aplicació/README.md)**

---

> **Nota:** Este és un projecte personal i independent. No està afiliat amb AWS.