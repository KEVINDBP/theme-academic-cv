---
# Leave the homepage title empty to use the site title
title: Kevin Darío Bejarano Palacios
date: 2025-10-21 # Fecha actualizada para referencia
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  # 1. BIOGRAFÍA Y RESUMEN
  - block: resume-biography-3
    content:
      # Asegúrate de que el nombre de usuario ('admin') esté correcto según tu carpeta 'content/authors/'
      username: admin
      # Se deja vacío para usar el texto que definiremos en la siguiente sección (Markdown)
      text: '' 
      # Botón para descargar CV
      button:
        text: Descargar CV
        url: uploads/resume.pdf
      # Dejamos estos títulos vacíos para no duplicar secciones en la página de inicio
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Aplica un fondo de gradiente
      css_class: hbx-bg-gradient
      # Personalización del Avatar
      avatar:
        size: medium 
        shape: circle
  
  # 2. PRESENTACIÓN PROFESIONAL (Perfil Abogado/Programador)
  - block: markdown
    content:
      title: 'Perfil Profesional'
      subtitle: 'Abogado, Magíster en Derecho Procesal Penal y Técnico en Programación de Software.'
      text: |-
        Soy **Kevin Darío Bejarano Palacios**, un profesional con un perfil único que combina el rigor legal y la especialización en **Derecho Procesal Penal** (Magíster), con sólidas habilidades en el desarrollo de software.
        
        Tengo amplio conocimiento en **Teoría del Delito** y domino varias herramientas de programación, lo que me permite abordar soluciones tecnológicas con una perspectiva legal y de sistemas.

        **Habilidades Técnicas Clave:**
        * **Backend:** C# con ASP.NET, Python (incluyendo Django).
        * **Frontend:** HTML, CSS y JavaScript.

        Interesado en proyectos que requieran la intersección de derecho, sistemas y automatización.
    design:
      columns: '1'

  # 3. HABILIDADES / EXPERIENCIA (Usando la sección de colección, si quieres destacar items específicos)
  # *Opcional: Si tienes experiencia laboral o habilidades bien definidas en las carpetas de 'experience' y 'skills', 
  # puedes añadir bloques de 'collection' aquí. Por ahora, dejamos las secciones irrelevantes eliminadas.*

  # --- SECCIONES ELIMINADAS ---
  # Se eliminaron los bloques 'Featured Publications', 'Recent Publications', 'Recent & Upcoming Talks' y 'Recent News' 
  # para que el CV se centre en tu experiencia y habilidades.

  # 4. CTA (Opcional, si quieres mantener la promoción de Hugo Blox)
  - block: cta-card
    # ... (contenido del cta-card)
    # Recomiendo ELIMINAR O COMENTAR este bloque en tu CV final.

---
