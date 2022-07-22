# Anonchat

An anonymous chat application where a user may enter a chat room and select
their desired username (which will be stored in their session). Users own
messages will be determined by assigning each session a UUID. Once the session
expires for that user they will enter a new username (which may be the same)
but their previous messages will not be highlighted as their own.

Built with:
- Svelte - front end framework
- SvelteKit - back end framework
- Supabase - Postgres database host and API to interface with the database
- DaisyUI (Tailwind CSS) for premade UI components and additional styling
