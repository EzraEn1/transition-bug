# SvelteKit Transition Bug

Do a `pnpm i` then `pnpm dev`.

Steps:

1. You are Home. (/)
2. Go Places. (/places)
3. Do things. Oh no, doThings is not found!
4. Go home. (/)
5. Go places. (/places) Yet you are still... home?


Does not appear to affect `in:[transition]`, but affects `transition:[transition]` and `out:[transition]`.