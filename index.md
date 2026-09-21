<style>
:root {
  --primary: #4f46e5;
  --secondary: #6366f1;
  --accent: #22c55e;
  --bg: #f8fafc;
  --text: #111827;
  --muted: #6b7280;
  --card: #ffffff;
  --border: #e5e7eb;
  --radius: 14px;
  --gap: 1rem;
}

/* Use the full available content width of the page. */
.portfolio-shell {
  width: 100%;
  max-width: none;
  margin: 0;
  padding: 0.5rem 0 1.5rem;
  box-sizing: border-box;
}

.portfolio-shell section {
  margin: 0 0 var(--gap);
}

.portfolio-shell section:last-child {
  margin-bottom: 0;
}

.portfolio-shell h1,
.portfolio-shell h2,
.portfolio-shell h3 {
  font-weight: 700;
  letter-spacing: -0.02em;
}

.portfolio-shell h1 {
  font-size: 2.25rem;
  line-height: 1.15;
  margin: 0 0 0.35rem;
}

.portfolio-shell h2 {
  color: var(--secondary);
  font-size: 1.3rem;
  line-height: 1.25;
  margin: 0 0 0.8rem;
}

.portfolio-shell h3 {
  font-size: 1.05rem;
  line-height: 1.3;
  margin: 0 0 0.3rem;
}

.portfolio-shell p {
  margin: 0.45rem 0;
}

/* Shared card treatment */
.card,
.hero-card,
.cta-card,
.proof-item {
  background: var(--card);
  border-radius: var(--radius);
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.05);
  box-sizing: border-box;
}

.card,
.hero-card,
.cta-card,
.proof-item {
  width: 100%;
}

.card {
  height: 100%;
  padding: 1.2rem 1.35rem;
  border: 1px solid var(--border);
}

.hero-card {
  padding: 1.75rem 2rem;
  border: 2px solid var(--primary);
}

.profile-container {
  display: flex;
  align-items: center;
  gap: 1.75rem;
  text-align: left;
}

.profile-image {
  flex: 0 0 auto;
}

.profile-image img {
  display: block;
  width: 135px;
  height: 135px;
  border: 0;
  border-radius: 50%;
  object-fit: cover;
  box-shadow: none;
}

.profile-text {
  min-width: 0;
}

.hero-role {
  color: var(--secondary);
  font-size: 1.06rem;
  font-weight: 650;
  margin: 0 0 0.5rem;
}

.focus-chips,
.opportunity-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.45rem;
  margin-top: 0.75rem;
}

.focus-chip,
.opportunity-tag {
  padding: 0.3rem 0.7rem;
  border: 1px solid #c7d2fe;
  border-radius: 999px;
  background: #eef2ff;
  color: #3730a3;
  font-size: 0.82rem;
  font-weight: 600;
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem;
  margin-top: 0.9rem;
}

.button {
  display: inline-block;
  padding: 0.52rem 0.9rem;
  border-radius: 8px;
  background: var(--primary);
  color: #fff !important;
  font-size: 0.88rem;
  font-weight: 650;
  line-height: 1.2;
  text-decoration: none !important;
}

.button.secondary {
  background: #eef2ff;
  color: #3730a3 !important;
  border: 1px solid #c7d2fe;
}

/* Three equal highlight cards. */
.proof-bar {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: var(--gap);
}

.proof-item {
  min-height: 88px;
  padding: 0.8rem 0.9rem;
  border: 1px solid var(--border);
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
}

.proof-item strong {
  display: block;
  color: var(--primary);
  font-size: 0.92rem;
  line-height: 1.25;
}

.proof-item span {
  display: block;
  color: var(--muted);
  font-size: 0.77rem;
  line-height: 1.35;
  margin-top: 0.2rem;
}

/* Full-width content cards. */
.two-column {
  display: grid;
  grid-template-columns: minmax(0, 1fr);
  gap: var(--gap);
  align-items: stretch;
}

.two-column > .card {
  width: 100%;
}

.project-preview + .project-preview {
  margin-top: 0.85rem;
  padding-top: 0.85rem;
  border-top: 1px solid var(--border);
}

.project-preview p {
  margin: 0.25rem 0 0;
}

.text-link {
  font-weight: 650;
}

/* Experience card */
.experience-item + .experience-item {
  margin-top: 0.85rem;
  padding-top: 0.85rem;
  border-top: 1px solid var(--border);
}

.experience-item h3 {
  margin: 0 0 0.18rem;
  font-size: 1rem;
}

.experience-item p {
  margin: 0.22rem 0;
  font-size: 0.88rem;
}

.experience-date {
  color: var(--muted);
  font-size: 0.78rem !important;
  font-weight: 600;
}

.experience-skills {
  display: flex;
  flex-wrap: wrap;
  gap: 0.35rem;
  margin-top: 0.5rem;
}

.experience-tag {
  display: inline-block;
  padding: 0.24rem 0.58rem;
  border: 1px solid #c7d2fe;
  border-radius: 999px;
  background: #eef2ff;
  color: #3730a3;
  font-size: 0.74rem;
  line-height: 1.25;
  font-weight: 600;
}

.compact-list {
  margin: 0.4rem 0 0;
  padding-left: 1.15rem;
}

.compact-list li {
  margin-bottom: 0.25rem;
}

/* CTA */
.cta-card {
  padding: 1.15rem 1.35rem;
  border: 1px solid var(--border);
  border-left: 4px solid var(--accent);
}

.cta-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
}

.socials {
  display: flex;
  flex: 0 0 auto;
  gap: 0.6rem;
}

.socials a {
  display: inline-flex;
  align-items: center;
  justify-content: center;
}

.socials img {
  display: block;
  width: 27px;
  height: 27px;
  filter: grayscale(1);
  transition: transform 0.2s ease, filter 0.2s ease;
}

.socials img:hover {
  filter: grayscale(0);
  transform: translateY(-2px);
}

.masthead__menu-item a {
  color: #4f46e5 !important;
}

/* Tablet / mobile */
@media (max-width: 900px) {
  .portfolio-shell {
    width: 100%;
    max-width: none;
  }

  .hero-card {
    padding: 1.5rem;
  }

  .two-column {
    grid-template-columns: minmax(0, 1fr);
  }
}

@media (max-width: 650px) {
  .portfolio-shell {
    width: 100%;
    max-width: none;
    padding-top: 0.25rem;
  }

  .profile-container {
    flex-direction: column;
    align-items: flex-start;
    gap: 1rem;
  }

  .profile-image img {
    width: 105px;
    height: 105px;
  }

  .portfolio-shell h1 {
    font-size: 1.9rem;
  }

  .proof-bar {
    grid-template-columns: 1fr;
  }

  .proof-item {
    min-height: 0;
    padding: 0.75rem 0.9rem;
  }

  .cta-content {
    flex-direction: column;
    align-items: flex-start;
  }

  .socials {
    margin-top: 0.15rem;
  }
}
</style>
