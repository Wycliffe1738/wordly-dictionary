
:root {
    font-family: Arial, Helvetica, sans-serif;
    color: #20213a;
    background: #f6f5ff;
    font-synthesis: none;
    --surface: #ffffff;
    --text: #20213a;
    --muted: #74748b;
    --accent: #6c4ce3;
    --border: #e7e4f2;
}

* {
    box-sizing: border-box;
}

body {
    margin: 0;
    min-height: 100vh;
    background: #f6f5ff;
    color: var(--text);
    transition: background 0.25s, color 0.25s;
}

button, input {
    font: inherit;
}

button {
    cursor: pointer;
}

.navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 7%;
    background: var(--surface);
    border-bottom: 1px solid var(--border);
}

.logo {
    font-size: 1.8rem;
    font-weight: 800;
    color: var(--text);
    text-decoration: none;
}

.logo span, .hero h1 span {
    color: var(--accent);
}

#theme-toggle {
    padding: 10px 14px;
    border: 1px solid var(--border);
    border-radius: 12px;
    background: var(--surface);
    color: var(--text);
}

.container {
    width: min(850px, 90%);
    margin: 0 auto;
}

.hero {
    padding: 65px 0 35px;
    text-align: center;
}

.eyebrow {
    color: var(--accent);
    font-size: 0.75rem;
    font-weight: 700;
    letter-spacing: 2px;
}

.hero h1 {
    margin: 16px 0;
    font-size: clamp(2rem, 5vw, 3.4rem);
    line-height: 1.15;
}

.subtitle {
    max-width: 570px;
    margin: 0 auto 28px;
    color: var(--muted);
    line-height: 1.7;
}

#search-form {
    display: flex;
    gap: 10px;
    max-width: 650px;
    margin: 0 auto;
    padding: 8px;
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 16px;
    box-shadow: 0 10px 30px #40308012;
}

#word-input {
    flex: 1;
    min-width: 0;
    padding: 14px;
    color: var(--text);
    background: transparent;
    border: none;
    outline: none;
}

#search-form:focus-within {
    outline: 2px solid var(--accent);
    outline-offset: 3px;
}

#search-button {
    padding: 14px 24px;
    border: none;
    border-radius: 10px;
    background: var(--accent);
    color: white;
    font-weight: 700;
}

.suggestions {
    color: var(--muted);
    font-size: 0.9rem;
}

.suggestion {
    margin: 4px;
    padding: 5px 9px;
    border: 1px solid var(--border);
    border-radius: 20px;
    background: var(--surface);
    color: var(--accent);
}

#status {
    text-align: center;
    color: var(--muted);
    min-height: 24px;
}

#status.error {
    color: #d12f49;
}

.word-card, .favorites-section {
    margin: 25px 0;
    padding: 28px;
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 20px;
    box-shadow: 0 8px 30px #4030800b;
}

.word-heading {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 15px;
}

.word-heading h2 {
    margin: 0;
    font-size: 2.3rem;
    overflow-wrap: anywhere;
}

#phonetic {
    color: var(--accent);
}

#audio-button, .favorite-button {
    padding: 10px 14px;
    border: 1px solid var(--border);
    border-radius: 10px;
    background: var(--surface);
    color: var(--accent);
}

.favorite-button {
    margin: 10px 0 20px;
}

.meaning {
    padding: 18px 0;
    border-top: 1px solid var(--border);
}

.meaning h3 {
    color: var(--accent);
    font-style: italic;
}

.meaning li {
    margin: 12px 0;
    line-height: 1.6;
}

.synonyms {
    color: var(--muted);
    line-height: 1.7;
}

.source {
    margin-top: 25px;
    color: var(--muted);
    font-size: 0.85rem;
}

.source a {
    color: var(--accent);
}

.section-heading {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 12px;
}

.section-heading h2 {
    margin-top: 5px;
}

#favorite-count {
    color: var(--muted);
    font-size: 0.9rem;
}

#empty-favorites {
    color: var(--muted);
}

#favorites-list {
    padding: 0;
    list-style: none;
}

#favorites-list li {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 10px;
    padding: 12px 0;
    border-top: 1px solid var(--border);
}

.favorite-word {
    border: none;
    background: transparent;
    color: var(--accent);
    font-weight: 700;
    text-align: left;
    overflow-wrap: anywhere;
}

.remove-favorite {
    border: none;
    background: transparent;
    color: #d12f49;
}

footer {
    padding: 25px;
    color: var(--muted);
    text-align: center;
    font-size: 0.85rem;
}

.sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap;
    border: 0;
}

[hidden] {
    display: none !important;
}

body.dark {
    --surface: #222139;
    --text: #f3f0ff;
    --muted: #bbb6d2;
    --border: #403b5a;
    --accent: #b5a1ff;
    background: #171629;
}

@media (max-width: 550px) {
    .navbar {
        padding: 16px 5%;
    }

    .hero {
        padding-top: 45px;
    }

    #search-form {
        gap: 4px;
    }

    #search-button {
        padding: 12px;
    }

    .word-card, .favorites-section {
        padding: 20px;
    }

    .word-heading h2 {
        font-size: 1.8rem;
    }
}
