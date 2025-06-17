# API Explorer: Mastering RESTful Connections

## Project Description

CineSeek is a modern movie discovery application built with **Next.js**, **TypeScript**, and **Tailwind CSS**. Users can browse movies from the MoviesDatabase API, view details, and search by year or genre. The project emphasizes responsive design, clean architecture, and robust API integration.

---

## Learning Objectives

- Understand API documentation and integration
- Implement TypeScript interfaces for API responses
- Create reusable React components
- Build responsive layouts with Tailwind CSS
- Manage state for filtering and pagination
- Handle errors and loading states effectively
- Set up Next.js API routes for server-side data fetching
- Manage environment variables for API keys

---

## Requirements

### Technical Stack

- Next.js 14 (Pages Router)
- TypeScript
- Tailwind CSS
- Font Awesome icons
- MoviesDatabase API

### Development Requirements

- Node.js (v16 or higher)
- npm or yarn
- Git

---

## File Structure

```
alx-movie-app/
├── components/
│   ├── commons/
│   │   ├── Button.tsx
│   │   ├── Loading.tsx
│   │   └── MovieCard.tsx
│   └── layouts/
│       ├── Footer.tsx
│       ├── Header.tsx
│       └── Layout.tsx
├── interfaces/
│   └── index.ts
├── pages/
│   ├── api/
│   │   └── fetch-movies.ts
│   ├── movies/
│   │   └── index.tsx
│   ├── _app.tsx
│   └── index.tsx
├── public/
├── styles/
│   └── globals.css
├── .env.local
├── .eslintrc.json
├── .gitignore
├── next.config.js
├── package.json
└── tsconfig.json
```

---

## Best Practices

### Code Quality

- Use TypeScript interfaces for all props and API responses
- Component-based architecture with clear separation of concerns
- Proper error handling in API requests
- Loading states for better UX
- Store sensitive data in environment variables

### Performance

- Client-side navigation with Next.js router
- Efficient API calls with pagination
- Responsive design with Tailwind CSS
- Image optimization using Next.js Image component

### Maintainability

- Consistent code formatting
- Clear folder structure
- Reusable components
- Comprehensive prop typing
- Proper documentation in README

---

## API Integration

**Endpoints:**

- `/titles`: Fetch movie data, filter by year/genre, supports pagination

**Authentication:**

- API key via headers
- Store API key in environment variables
- Use server-side API route to protect keys

**Error Handling:**

- Loading component for pending states
- Try/catch in API routes
- Status code checks
- Type guards for API data

**Usage Limits:**

- Consider API rate limits
- Use pagination to limit request size
- Client-side caching where appropriate
- Error boundaries for graceful failure
