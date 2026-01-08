# 🚀 fnPrompt - AI Prompt Architect

[![Website](https://img.shields.io/website?url=https%3A%2F%2Ffnprompt.com)](https://fnprompt.com)
[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Available-blue?logo=google-chrome&logoColor=white)](https://chrome.google.com/webstore)
[![CLI](https://img.shields.io/badge/CLI-Terminal_Tool-black?logo=gnubash&logoColor=white)](#)
[![License](https://img.shields.io/badge/license-Proprietary-red)](https://fnprompt.com)

**[English](#english) | [Türkçe](#türkçe)**

---

<a name="english"></a>
## 🇬🇧 English

### What is fnPrompt?

**fnPrompt** is a comprehensive ecosystem (Web, Extension, CLI) designed to bridge the gap between human ideas and complex Artificial Intelligence interactions. It acts as an "Elite Prompt Architect," transforming vague user inputs into sophisticated, structured "System Prompts" that unlock the full potential of LLMs like ChatGPT, Claude, and Gemini.

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

#### 2. The Chrome Extension
The fnPrompt Chrome Extension takes productivity to the next level by integrating your prompt library directly into your workflow.

* **Instant Access:** Access the entire community library and your personal collection without leaving your current tab.
* **Smart Injection (One-Click Paste):** The extension detects active AI chat interfaces (like ChatGPT, Claude, Gemini) and injects the selected prompt directly into the input field with a single click.
* **Real-Time Search:** Quickly find specific prompts using the built-in search bar.
* **Seamless Sync:** Any prompt saved on the website is instantly available in the extension.

#### 3. The CLI Tool (Terminal)
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

1.  **Ideation:** The user inputs a raw idea via Web, Extension, or CLI.
2.  **Architecture:** The centralized backend processes the input and structures it into a professional prompt.
3.  **Storage:** The result is saved to the user's collection and synced across all platforms.
4.  **Deployment:**
    * **Web:** Copy manually.
    * **Extension:** One-click injection into AI tools.
    * **CLI:** Auto-copy to system clipboard.

### 🔒 Privacy & Security

* **Authentication:** Secure Google OAuth integration for web; Token-based authentication for CLI.
* **Data Protection:** Private prompts are strictly isolated and never shown in public feeds.
* **Minimal Permissions:** The Chrome extension only activates injection scripts when explicitly triggered by the user.

---

<a name="türkçe"></a>
## 🇹🇷 Türkçe

### fnPrompt Nedir?

**fnPrompt**, insan düşünceleri ile karmaşık Yapay Zeka etkileşimleri arasındaki boşluğu doldurmak için tasarlanmış kapsamlı bir ekosistemdir (Web, Eklenti, Terminal). Bir "Elit Prompt Mimarı" gibi davranarak, kullanıcıların aklındaki kaba fikirleri; *Persona, Amaç, Bağlam ve Kurallar* içeren profesyonel "Sistem Promptlarına" dönüştürür.

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

#### 2. Chrome Eklentisi
fnPrompt Chrome Eklentisi, kütüphanenizi doğrudan çalışma alanınıza taşıyarak üretkenliğinizi artırır.

* **Anında Erişim:** Bulunduğunuz sekmeden ayrılmadan tüm topluluk kütüphanesine ve kişisel koleksiyonunuza erişin.
* **Akıllı Yapıştırma (Tek Tıkla Entegrasyon):** Eklenti, açık olan yapay zeka aracını (ChatGPT, Claude, Gemini vb.) algılar ve seçtiğiniz promptu tek tıkla otomatik olarak yazı alanına yazar.
* **Anlık Arama:** Eklenti içindeki arama çubuğu ile binlerce prompt arasından ihtiyacınız olanı saniyeler içinde bulun.
* **Kesintisiz Senkronizasyon:** Web sitesinde kaydettiğiniz bir prompt, anında eklentide belirir.

#### 3. CLI Aracı (Terminal)
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

1.  **Fikir:** Kullanıcı ham fikrini Web, Eklenti veya CLI üzerinden girer.
2.  **Mimari:** Merkezi backend sistemi bu girdiyi işler ve profesyonel bir prompt formatına dönüştürür.
3.  **Saklama:** Sonuç, kullanıcının koleksiyonuna kaydedilir ve tüm platformlarda senkronize olur.
4.  **Kullanım:**
    * **Web:** Manuel kopyalama.
    * **Eklenti:** Yapay zeka araçlarına tek tıkla enjekte etme.
    * **CLI:** Sistem panosuna otomatik kopyalama.

### 🔒 Gizlilik ve Güvenlik

* **Kimlik Doğrulama:** Web için Güvenli Google OAuth; CLI için Token bazlı kimlik doğrulama.
* **Veri Koruma:** Gizli olarak işaretlenen promptlar kesinlikle izole edilir ve topluluk akışlarında gösterilmez.
* **Minimum İzinler:** Chrome eklentisi, yalnızca kullanıcı "Kopyala & Yapıştır" butonuna bastığında ilgili komut dosyalarını çalıştırır.

---

### 📬 Contact / İletişim

Project Website: [fnprompt.com](https://fnprompt.com)  
Support: info@fnprompt.com
