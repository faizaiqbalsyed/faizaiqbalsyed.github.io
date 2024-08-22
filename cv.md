---
layout: default
title: CV
---

<style>
/* CV Section Styles */
.cv-section {
    margin: 2rem auto;
    padding: 1.5rem;
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.cv-section h2 {
    font-size: 1.875rem; /* Font size for h2 */
    margin-bottom: 1rem;
    color: #004b8d; /* Heading color */
}

.cv-section p {
    font-size: 1.125rem;
    margin-bottom: 1.5rem;
    color: #333;
}

.cv-buttons {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    align-items: center;
}

.cv-button {
    display: inline-flex;
    align-items: center;
    padding: 0.75rem 1.5rem;
    font-size: 1.125rem;
    font-weight: bold;
    color: #fff;
    background-color: #004b8d;
    border-radius: 8px;
    text-decoration: none;
    transition: background-color 0.3s ease, transform 0.3s ease, box-shadow 0.3s ease;
    position: relative;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.cv-button:hover {
    background-color: #5bacfc;
    transform: scale(1.05);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
}

.cv-button::after {
    content: '';
    position: absolute;
    top: 50%;
    left: 50%;
    width: 300%;
    height: 300%;
    background: rgba(255, 255, 255, 0.2);
    transform: translate(-50%, -50%) scale(0);
    transition: transform 0.5s ease;
    border-radius: 50%;
}

.cv-button:hover::after {
    transform: translate(-50%, -50%) scale(1);
}
</style>

<!-- CV Section -->
<section class="cv-section">
    <h2>CV</h2>
    <p>You can download my CV from the link below:</p>
    <div class="cv-buttons">
        <a href="https://faizaiqbalsyed.github.io/Faiza_Iqbal.pdf" class="cv-button cv-button-english" download>
            Download English CV
        </a>
        
    </div>
</section>
