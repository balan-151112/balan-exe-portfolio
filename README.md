# BALAN.EXE: Portfolio of Dharani Balan S L

React + Vite + Framer Motion + Lucide. No backend, no TypeScript.

```bash
npm install
npm run dev      # http://localhost:5173
npm run build
npm run preview
```

## Edit your content
| What | File |
|---|---|
| Name, links, education, resume path | `src/data/profile.js` |
| Skills + level labels (Learning / Familiar / Practicing) | `src/data/skills.js` |
| Projects (add real GitHub/demo URLs here) | `src/data/projects.js` |
| Certifications (empty array shows an empty state) | `src/data/certifications.js` |

## Contact details
- Email: `dharani151112@gmail.com` (shown in Contact/footer)
- LinkedIn: `https://www.linkedin.com/in/dharani-balan-s-l`
- `VITE_EMAILJS_SERVICE_ID`, `VITE_EMAILJS_TEMPLATE_ID`, `VITE_EMAILJS_PUBLIC_KEY`: enables the contact form.
  EmailJS template variables: `from_name`, `from_email`, `subject`, `message`, `to_name`.
  Without these the form validates but clearly states the message was NOT sent.

## Resume
Your resume is included at `public/resume/Dharani_Balan_Resume.pdf`.
Certificate images: put them in `public/assets/certs/` and set `image` in `certifications.js`.
