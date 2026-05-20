# Deployment Log — LuxuryConnect Landing

## 2026-05-20

### Phase 1 — Dossier de travail [DONE]
- `/opt/luxuryconnect-landing/` créé

### Phase 2 — index.html [DONE]
- Fichier écrit : 244 lignes, HTML valide (balise </html> présente)
- Test taille : non vide ✓

### Phase 3 — README.md + .gitignore [DONE]
- README.md créé
- .gitignore créé

### Phase 4 — Git init + commit + GitHub push [DONE]
- Git configuré : user.name=dbf-digital / user.email=directbusinessfactory@gmail.com
- Commit initial : bc0fe8f "feat: initial landing page"
- Repo créé : https://github.com/dbf-digital/luxuryconnect-landing (public)
- Branch main pushée, tracking origin/main ✓

### Phase 5 — Test local HTML [DONE]
- Fichier non vide ✓
- HTML complet (</html> trouvé) ✓
- Lignes : 244 (>200 requis) ✓

### Phase 6 — Instructions Coolify [DONE]
- Instructions affichées et appliquées par l'utilisateur
- Fix appliqué : domaines re-saisis en https://luxuryconnect.fr et https://www.luxuryconnect.fr
- Publish Directory laissé vide (pas de slash)

### Phase 7 — Vérification post-déploiement [DONE]
- DNS luxuryconnect.fr → 163.172.51.249 ✓
- DNS www.luxuryconnect.fr → 163.172.51.249 ✓
- HTTP → redirect HTTPS 307 ✓
- HTTPS luxuryconnect.fr → HTTP/2 200 ✓
- Certificat Let's Encrypt (R13) valide jusqu'au 2026-08-18 ✓
- Titre HTML : "LuxuryConnect — Votre commercial IA. Vous restez maître." ✓
- www.luxuryconnect.fr : contenu OK, propagation DNS en cours ✓
