# @supabase/auth-helpers-sveltekit

## 0.9.4

### Patch Changes

- Updated dependencies [04a7249]
- Updated dependencies [04a7249]
  - @supabase/auth-helpers-shared@0.3.4

## 0.9.3

### Patch Changes

- Updated dependencies [1ea258e]
  - @supabase/auth-helpers-shared@0.3.3

## 0.9.2

### Patch Changes

- Updated dependencies [185e9cf]
  - @supabase/auth-helpers-shared@0.3.2

## 0.9.1

### Patch Changes

- Updated dependencies [f86073d]
  - @supabase/auth-helpers-shared@0.3.1

## 0.9.0

### Minor Changes

- 192f85c: SvelteKit rework:
  - separate server and client authentication [9bf88f7](https://github.com/supabase/auth-helpers/pull/457/commits/9bf88f76d3124f758394720de84c722052660546)
  - update supabase-js to 2.7.0 [6a18a94](https://github.com/supabase/auth-helpers/pull/457/commits/6a18a940f4e5ffde022580daf37ba40750637ec1)
  - update examples [0bef909](https://github.com/supabase/auth-helpers/pull/457/commits/0bef909d912efdf020b24a9d653d2f34080cd107)
  - use tsup for constants [1da1f67](https://github.com/supabase/auth-helpers/pull/457/commits/1da1f672c020b55103e564137150932b1c122b2c)

### Patch Changes

- Updated dependencies [33c8a81]
  - @supabase/auth-helpers-shared@0.3.0

## 0.8.7

### Patch Changes

- d3366e4: Allow passing client options
- Updated dependencies [d3366e4]
  - @supabase/auth-helpers-shared@0.2.4

## 0.8.6

### Patch Changes

- Updated dependencies [bee77c7]
  - @supabase/auth-helpers-shared@0.2.3

## 0.8.5

### Patch Changes

- Updated dependencies [999e57e]
  - @supabase/auth-helpers-shared@0.2.2

## 0.8.4

### Patch Changes

- 075a92f: sveltekit ssr disable auto token refresh

## 0.8.3

### Patch Changes

- 2fda843: Switch to refreshSession
- 2fda843: update supabase-js
- Updated dependencies [2fda843]
- Updated dependencies [2fda843]
  - @supabase/auth-helpers-shared@0.2.1

## 0.8.2

### Patch Changes

- 8f6a474: Fix type issue in the getServerSession function

## 0.8.1

### Patch Changes

- 7a6377a: Add fix for esm package build
- 7a6377a: Remove old files from 0.7.x

## 0.8.0

### Minor Changes

- 58e6287: Update to supabase-js v2

## 0.7.1

### Patch Changes

- 3a09401: Add type intellisense for @supabase/auth-helpers-sveltekit/server
  Add .js to fix ERR_MODULE_NOT_FOUND (can´t use the script, it throws an error @sveltejs/kit/hooks not found)
  Pass page store and invalidation to startSupabaseSessionSync as \$app module is not available in npm packages

## 0.7.0

### Minor Changes

- cd9150c: [breaking] Update to work with latest SvelteKit RC

## 0.6.11

### Patch Changes

- Updated dependencies [63b1da0]
  - @supabase/auth-helpers-shared@0.1.4

## 0.6.10

### Patch Changes

- 0ab05cf: Update format of x-client-info header

## 0.6.9

### Patch Changes

- 50669a6: Add x-client-info header to show package name and version

## 0.6.8

### Patch Changes

- 8e0b747: Change error handling to not show flow disruption errors

## 0.6.7

### Patch Changes

- 0298db1: Rename skHelper method to createSupabaseClient

## 0.6.6

### Patch Changes

- 56228e3: Remove the need for user to create /api/auth/user and /api/auth/callback endpoints
- 56228e3: Add getProviderToken helper method
- Updated dependencies [56228e3]
  - @supabase/auth-helpers-shared@0.1.3

## 0.6.5

### Patch Changes

- 69fefcb: Change logger to be a wrapper for console

## 0.6.4

### Patch Changes

- 38ccf1c: Logger can be imported in your own project for setting log levels
- Updated dependencies [38ccf1c]
  - @supabase/auth-helpers-shared@0.1.2

## 0.6.3

### Patch Changes

- 9dda264: Add better error handling and error codes
- 9dda264: Fix supabaseServerClient with request and withApiAuth return type
- Updated dependencies [9dda264]
  - @supabase/auth-helpers-shared@0.1.1

## 0.6.2

### Patch Changes

- d23b268: [breaking change] Update the getUser function to only get the user and not save the token
- 1c95004: Add new handleAuth function to export all hooks as an array to destructure
- 588d329: Add handleLogout hook for logging out via endpoint /api/auth/logout

## 0.6.1

### Patch Changes

- 2f2abf2: Fix session being overwritten in SupaAuthHelper

## 0.6.0

### Minor Changes

- 1e56b35: Add file extension to es modules imports

## 0.5.0

### Minor Changes

- f854c7f: Remove unused helper files

## 0.4.0

### Minor Changes

- 865cc4a: Update packages to compile to esm

## 0.3.0

### Minor Changes

- f399820: Using shared package as a dependency
  Update sveltekit package with latest code to update tokens

## 0.2.0

### Minor Changes

- 5d741ae: Remove svelte-preprocess from sveltekit package

## 0.1.0

### Minor Changes

- de01c86: Initial release of svelte integration
