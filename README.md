# Rick and Morty React III

By the end of this assignment your project should meet the following requirements:
  
  - CharacterDetailsPage.jsx should display all the information pertaining to a single character. Ensure to utilize useParams.
  - A dynamic route that will display CharacterDetailsPage.jsx
  - Implement a functionality for useNavigate through your program

## Hints

- Keep working in your Rick and Morty React II project.
- The dynamic route is another child of App in `router.jsx`, for example `{ path: 'characters/:id', element: <CharacterDetailsPage /> }`. Inside the page, `useParams()` gives you `{ id }`, and `https://rickandmortyapi.com/api/character/${id}` returns that one character.
- Import `useParams` and `useNavigate` from `'react-router'`. `useNavigate` replaced the old `useHistory` / `history.push`, so skip tutorials that use those.
