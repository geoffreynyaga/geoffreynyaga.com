

## Design System

### Philosophy
- Inspired by Linear, Vercel, Notion, and Stripe design systems
- Clean, minimal, professional without looking generic or AI-generated
- Prioritize readability and whitespace over decoration
- No left-border cards, no excessive drop shadows, no gradient backgrounds
- Subtle hover interactions only

### Visual Language
- Kenyan color palette used sparingly: Green (#15b236), Red (#dd0000), Black, White
- Green for tags and category labels only
- Black for primary buttons and text
- Gray scale for secondary text and borders
- Clean white or light gray (#fafafa) alternating section backgrounds

### Typography
- Inter for body text (clean, modern, highly readable)
- Newsreader (serif) for headings (adds personality without being loud)
- Font weights: 400 body, 500 labels, 600-700 headings
- No all-caps except for tiny labels (0.75rem)
- Letter-spacing: negative for headings (-0.01em to -0.02em)

### Layout Patterns
- Sticky header with blur backdrop
- Full-width sections alternating white/gray backgrounds
- Max-width containers (1100px for content, 720px for hero text)
- Project rows as horizontal grid (name | description | stack)
- Work cards as 3-column grid with minimal borders
- No card shadows, use border-color transitions on hover

### Components
- **Buttons**: Solid black primary, outlined secondary with gray border
- **Cards**: 1px border #e4e4e7, 12px radius, 2rem padding, hover changes border color
- **Tags**: Tiny uppercase, green color, no background
- **Links**: No underline by default, color transition on hover
- **Sections**: 5rem vertical padding, clear h2 headers with serif font

### Responsive Behavior
- 3-column to 2-column to 1-column grid breakpoints
- Header nav hidden on mobile
- Full-width buttons on mobile
- Stack project rows vertically on mobile

### What to Avoid
- Left-border accent cards (looks dated)
- Heavy shadows or glass effects
- Bright color backgrounds (yellow/orange hero sections)
- Decorative circles, dashed borders, hand-drawn elements
- Generic "tech" aesthetics (blue gradients, neon accents)
- Em dashes, emojis, or excessive decoration

## Content Structure

### Header
- Logo initials (GN)
- Navigation: About, Work, Projects, YouTube

### Hero Section
- Location badge pill ("Based in Kenya")
- Name in large serif font
- Role list (comma-separated, not bullets)
- Brief intro paragraph (2 sentences max)
- Primary CTA buttons (GitHub, YouTube)

### About Section
- Two-column layout: prose left, details right
- Details as label/value pairs (Stack, Focus, Community)

### Selected Work Section
- 3-column card grid
- Each card: tag, title, description, tech stack
- Tags indicate domain (Enterprise, Aviation, AI)

### Projects Section
- Horizontal row layout (table-like)
- Name | Description | Stack columns
- Linked projects have hover state

### Latest Videos Section
- 3-column card grid
- Video title + type (Tutorial/Playlist)
- "View all" link below

### Footer
- Horizontal link list
- Simple copyright/name

## Technical Notes
- Using scoped Astro styles (not Tailwind currently)
- CSS custom properties for color consistency
- Google Fonts: Inter, Newsreader
- Mobile-first responsive with 640px and 900px breakpoints

