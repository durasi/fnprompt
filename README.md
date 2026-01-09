# 🚀 fnPrompt - AI Prompt Architect

[![Website](https://img.shields.io/website?url=https%3A%2F%2Ffnprompt.com)](https://fnprompt.com)
[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Available-blue?logo=google-chrome&logoColor=white)](https://chrome.google.com/webstore/detail/fnprompt-ai-prompt-archit/jppkhigpabafljnbcgbpepnlkggidgnp)
[![Firefox Add-on](https://img.shields.io/badge/Firefox_Add--ons-Available-orange?logo=firefox-browser&logoColor=white)](https://addons.mozilla.org/en-US/firefox/addon/fnprompt-ai-prompt-architect/)
[![VS Code](https://img.shields.io/badge/VS%20Code-Marketplace-007ACC?logo=visualstudiocode&logoColor=white)](https://marketplace.visualstudio.com/items?itemName=fnprompt.fnprompt-vscode)
[![CLI](https://img.shields.io/badge/CLI-Terminal_Tool-black?logo=gnubash&logoColor=white)](#)
[![License](https://img.shields.io/badge/license-Proprietary-red)](https://fnprompt.com)

**[English](#english) | [Türkçe](#türkçe)**

---

<a name="english"></a>
## 🇬🇧 English

### What is fnPrompt?

**fnPrompt** is a comprehensive ecosystem (Web, Extension, VS Code, CLI) designed to bridge the gap between human ideas and complex Artificial Intelligence interactions. It acts as an "Elite Prompt Architect," transforming vague user inputs into sophisticated, structured "System Prompts" that unlock the full potential of LLMs like ChatGPT, Claude, and Gemini.

Whether you are a casual user or a developer, fnPrompt helps you organize, generate, and deploy high-quality prompts instantly.

### 🌟 Key Features

#### 1. The Web Platform (fnprompt.com)
The core of the ecosystem is a robust web application built for speed and community interaction.

* **AI Prompt Generation:** Users simply describe their idea (e.g., "A coding tutor for Python"). The system uses advanced algorithms to engineer a detailed prompt structure including *Persona, Objective, Context, Constraints, and Output Format*.
* **Multi-Language Support:** The interface and prompt generation support 10+ languages including English, Turkish, German, Spanish, Arabic, and Japanese.
* **Community Library:** A voting system allowing users to discover the most effective prompts created by the community.
* **Personal Collection:** Users can save their favorite prompts.
* **Privacy Controls:** Users have the option to save prompts as **"Public"** (shared with the community) or **"Private"** (encrypted and visible only to the user).
* **User Profiles:** Custom nicknames and avatar visibility settings for privacy-conscious users.

#### 2. Visual Studio Code Extension
**NEW!** Bring the power of fnPrompt directly into your IDE.

* **Right-Click & Generate:** Highlight any text or code comment, right-click, and select `fnPrompt: Refactor`.
* **Flow State:** Generate professional system prompts without leaving your editor.
* **Side-by-Side:** Opens the generated prompt in a new editor window for easy copying or editing.
* **[Download for VS Code](https://marketplace.visualstudio.com/items?itemName=fnprompt.fnprompt-vscode)**

#### 3. The Chrome Extension
The fnPrompt Chrome Extension takes productivity to the next level by integrating your prompt library directly into your workflow.

* **Instant Access:** Access the entire community library and your personal collection without leaving your current tab.
* **Smart Injection (One-Click Paste):** The extension detects active AI chat interfaces (like ChatGPT, Claude, Gemini) and injects the selected prompt directly into the input field with a single click.
* **Real-Time Search:** Quickly find specific prompts using the built-in search bar.
* **Seamless Sync:** Any prompt saved on the website is instantly available in the extension.

#### 4. The Firefox Extension
**NEW!** Seamlessly integrate fnPrompt into your Mozilla Firefox browser.

* **Cross-Browser Support:** Enjoy the same powerful features as the Chrome extension, now on Firefox.
* **Smart Injection:** Automatically injects prompts into AI tools like ChatGPT and Claude directly from the extension popup.
* **Privacy Focused:** Built with Mozilla's strict privacy standards in mind.
* **[Get it for Firefox](https://addons.mozilla.org/en-US/firefox/addon/fnprompt-ai-prompt-architect/)**

#### 5. The CLI Tool (Terminal)
For developers and command-line enthusiasts, fnPrompt offers a powerful CLI tool to generate and manage prompts directly from the terminal.

* **Generate & Copy:** Generate a professional prompt and automatically copy it to your clipboard with a single command.
* **Token-Based Auth:** Securely login using a generated token from the web dashboard.
* **Access Anywhere:** View your private collection or community feeds without opening a browser.

**Available Commands:**

| Command | Description |
| :--- | :--- |
| `fnprompt gen "your idea"` | Generates a prompt based on your idea and **copies it to clipboard**. |
| `fnprompt login <token>` | Logs you in. (Get your token at fnprompt.com/cli) |
| `fnprompt my` | Lists your personal prompt collection. |
| `fnprompt community` | Lists the latest community prompts. |
| `fnprompt logout` | Logs out and removes local credentials. |

### 🛠️ How It Works

1.  **Ideation:** The user inputs a raw idea via Web, Extensions, VS Code, or CLI.
2.  **Architecture:** The centralized backend processes the input and structures it into a professional prompt.
3.  **Storage:** The result is saved to the user's collection and synced across all platforms.
4.  **Deployment:**
    * **Web:** Copy manually.
    * **VS Code:** Open in new editor tab.
    * **Extensions:** One-click injection into AI tools.
    * **CLI:** Auto-copy to system clipboard.

### 🔒 Privacy & Security

* **Authentication:** Secure Google OAuth integration for web; Token-based authentication for CLI.
* **Data Protection:** Private prompts are strictly isolated and never shown in public feeds.
* **Minimal Permissions:** The browser extensions only activate injection scripts when explicitly triggered by the user.

---

<a name="türkçe"></a>
## 🇹🇷 Türkçe

### fnPrompt Nedir?

**fnPrompt**, insan düşünceleri ile karmaşık Yapay Zeka etkileşimleri arasındaki boşluğu doldurmak için tasarlanmış kapsamlı bir ekosistemdir (Web, Eklenti, VS Code, Terminal). Bir "Elit Prompt Mimarı" gibi davranarak, kullanıcıların aklındaki kaba fikirleri; *Persona, Amaç, Bağlam ve Kurallar* içeren profesyonel "Sistem Promptlarına" dönüştürür.

fnPrompt, hem bireysel kullanıcılar hem de geliştiriciler için ChatGPT, Claude ve Gemini gibi modellerden en yüksek verimi almayı sağlar.

### 🌟 Temel Özellikler

#### 1. Web Platformu (fnprompt.com)
Ekosistemin merkezi, hız ve topluluk etkileşimi için optimize edilmiş güçlü bir web uygulamasıdır.

* **Yapay Zeka Prompt Üretimi:** Kullanıcı sadece fikrini yazar (örn: "Python öğreten bir öğretmen"). Sistem arka planda bu fikri işleyerek profesyonel kalıplara sahip, detaylı bir prompt çıktısı üretir.
* **Çoklu Dil Desteği:** İngilizce, Türkçe, Almanca, İspanyolca, Arapça ve Japonca dahil 10'dan fazla dil desteği.
* **Topluluk Kütüphanesi:** Kullanıcıların oluşturduğu en iyi promptların oylandığı ve listelendiği dinamik bir akış.
* **Kişisel Koleksiyon:** Üretilen promptları daha sonra kullanmak üzere kaydetme imkanı.
* **Gizlilik Kontrolleri:** Kullanıcılar promptlarını **"Herkese Açık"** (toplulukla paylaşılır) veya **"Sadece Ben"** (gizli ve şifreli) olarak kaydedebilir.
* **Kullanıcı Profilleri:** Gizliliğe önem verenler için takma isim (nickname) ve avatar gizleme seçenekleri.

#### 2. Visual Studio Code Eklentisi
**YENİ!** fnPrompt gücünü doğrudan kod editörünüze taşıyın.

* **Sağ Tıkla & Üret:** Kod içindeki bir yorum satırını veya metni seçin, sağ tıklayıp `fnPrompt: Refactor` diyerek saniyeler içinde prompt üretin.
* **Odak Modu:** Tarayıcıya gitmenize gerek kalmadan, editör içinde AI promptları oluşturun.
* **Yeni Pencere:** Sonucu yan sekmede açar, düzenlemenize imkan tanır.
* **[VS Code için İndir](https://marketplace.visualstudio.com/items?itemName=fnprompt.fnprompt-vscode)**

#### 3. Chrome Eklentisi
fnPrompt Chrome Eklentisi, kütüphanenizi doğrudan çalışma alanınıza taşıyarak üretkenliğinizi artırır.

* **Anında Erişim:** Bulunduğunuz sekmeden ayrılmadan tüm topluluk kütüphanesine ve kişisel koleksiyonunuza erişin.
* **Akıllı Yapıştırma (Tek Tıkla Entegrasyon):** Eklenti, açık olan yapay zeka aracını (ChatGPT, Claude, Gemini vb.) algılar ve seçtiğiniz promptu tek tıkla otomatik olarak yazı alanına yazar.
* **Anlık Arama:** Eklenti içindeki arama çubuğu ile binlerce prompt arasından ihtiyacınız olanı saniyeler içinde bulun.
* **Kesintisiz Senkronizasyon:** Web sitesinde kaydettiğiniz bir prompt, anında eklentide belirir.

#### 4. Firefox Eklentisi
**YENİ!** fnPrompt deneyimini Mozilla Firefox tarayıcınıza taşıyın.

* **Tam Uyumluluk:** Chrome eklentisindeki tüm özelliklerin aynısı artık Firefox'ta.
* **Akıllı Entegrasyon:** Eklenti penceresinden ChatGPT ve Claude gibi araçlara tek tıkla prompt aktarın.
* **Gizlilik Odaklı:** Mozilla'nın yüksek gizlilik standartlarına uygun olarak geliştirildi.
* **[Firefox için İndir](https://addons.mozilla.org/en-US/firefox/addon/fnprompt-ai-prompt-architect/)**

#### 5. CLI Aracı (Terminal)
Geliştiriciler ve terminal tutkunları için fnPrompt, tüm işlemleri komut satırından yapmanızı sağlayan güçlü bir CLI aracı sunar.

* **Üret & Kopyala:** Tek bir komutla profesyonel prompt üretin ve sonucu otomatik olarak panonuza kopyalayın.
* **Token Bazlı Giriş:** Web panelinden alacağınız özel token ile güvenli giriş yapın.
* **Her Yerden Erişim:** Tarayıcı açmadan özel koleksiyonunuza veya topluluk akışına erişin.

**Kullanılabilir Komutlar:**

| Komut | Açıklama |
| :--- | :--- |
| `fnprompt gen "fikriniz"` | Fikrinize uygun prompt üretir ve **otomatik kopyalar**. |
| `fnprompt login <token>` | Giriş yapar. (Token almak için: fnprompt.com/cli) |
| `fnprompt my` | Kişisel prompt koleksiyonunuzu listeler. |
| `fnprompt community` | Topluluktaki son promptları listeler. |
| `fnprompt logout` | Çıkış yapar ve yerel verileri temizler. |

### 🛠️ Nasıl Çalışır?

1.  **Fikir:** Kullanıcı ham fikrini Web, Eklentiler, VS Code veya CLI üzerinden girer.
2.  **Mimari:** Merkezi backend sistemi bu girdiyi işler ve profesyonel bir prompt formatına dönüştürür.
3.  **Saklama:** Sonuç, kullanıcının koleksiyonuna kaydedilir ve tüm platformlarda senkronize olur.
4.  **Kullanım:**
    * **Web:** Manuel kopyalama.
    * **VS Code:** Editör içinde yeni pencere.
    * **Eklentiler:** Yapay zeka araçlarına tek tıkla enjekte etme.
    * **CLI:** Sistem panosuna otomatik kopyalama.

### 🔒 Gizlilik ve Güvenlik

* **Kimlik Doğrulama:** Web için Güvenli Google OAuth; CLI için Token bazlı kimlik doğrulama.
* **Veri Koruma:** Gizli olarak işaretlenen promptlar kesinlikle izole edilir ve topluluk akışlarında gösterilmez.
* **Minimum İzinler:** Tarayıcı eklentileri, yalnızca kullanıcı "Kopyala & Yapıştır" butonuna bastığında ilgili komut dosyalarını çalıştırır.

---

### 📬 Contact / İletişim

Project Website: [fnprompt.com](https://fnprompt.com)  
Support: info@fnprompt.com
