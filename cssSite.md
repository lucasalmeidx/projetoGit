* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root{
    --bg-color: #f8fafc;
    --text-color: #1e293b;
    --accent-color: #2563eb;
    --header-bg: #e2e8f0;
    --footer-bg: #e2e8f0;
    --button-hover: #1d4ed8;
    --font-main: "Poppins", sans-serif;
}

.dark-mode {
    --bg-color: #0f172a;
    --text-color: #e2e8f0;
    --accent-color: #3b82f6;
    --header-bg: #1e293b;
    --footer-bg: #0f172a;
    --button-hover: #2563eb;
}

body {
    font-family: var(--font-main);
    background-color: var(--bg-color);
    color: var(--text-color);
    line-height: 1.6;
}


header {
    background-color: var(--header-bg);
    padding: 20px;
    text-align: center;
    box-shadow: 0 2px 10px rgba(0,0,0,0.4);
}

header h1{
    font-size: 1.8rem;
    margin-bottom: 10px;
}

nav {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 15px;
}

nav a {
    color: var(--text-color);
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
}

nav a:hover {
    color: var(--accent-color);
}

#toggle-theme {
    background-color: var(--accent-color);
    color: white;
    border: none;
    padding: 8px 16px;
    border-radius: 8px;
    cursor: pointer;
    font-size: 0.9rem;
    transition: background-color 0.3s ease;
}

#toggle-theme:hover {
    background-color: var(--button-hover);
}

.intro {
    text-align: center;
    padding: 80px 20px;
    max-width: 800px;
    margin: 0 auto;
}

.intro h2{
    font-size: 2rem;
    color: var(--accent-color);
    margin-bottom: 20px;
}

.intro p{
    font-size: 1.1rem;
    margin-bottom: 30px;
}

button {
    background-color: var(--accent-color);
    color: white;
    border: none;
    padding: 12px 24px;
    border-radius: 8px;
    cursor: pointer;
    font-size: 1rem;
    transition: background-color 0.3s ease, transform 0.2, ease;
}

button a:hover {
    background-color: var(--accent-color);
    transform: scale(1.05);
}

footer {
    text-align: center;
    padding: 20px;
    background-color:var(--footer-bg);
    border-top: 1px solid #cbd5e1;
    color:#64748b;
    font-size: 0.9rem;
}


@media(max-widht: 768px){
    header h1 {
        font-size: 1.5rem;
    }

    .intro h2 {
        font-size: 1.6rem;
    }

    nav a {
        font-size: 0.95rem;
    }
}

@media(max-width: 480px){
    .intro {
        padding: 60px 15px;
    }

    button {
        width: 100px;
        padding: 14px;
    }
}

@media (max-widht: 480px){
    .intro{
        padding: 60px 15px;
    }

    button,
        #toggle-theme{
            width: 100%;
            padding: 14px;
        }
}