# sdk-js

Path: /Users/mlapointe/git/opencode/packages/sdk/js/src
Files: 38

## File Tree (by top-level directory)

- `client.ts` → * from "./gen/types.gen.js" (55 ln)
- `client.gen.ts` → type CreateClientConfig<T extends DefaultClientOptions = ClientOptions> = ( (22 ln)
- `client.gen.ts` → const createClient = (config: Config = {}): Client => { (212 ln)  [gen/]
- `index.ts` → type { Auth } from "../core/auth.gen.js" (25 ln)  [gen/]
- `types.gen.ts` → type ResponseStyle = "data" | "fields" (222 ln)  [gen/]
- `utils.gen.ts` → const createQuerySerializer = <T = unknown>({ allowReserved, array, object }: Qu (287 ln)  [gen/]
- `auth.gen.ts` → type AuthToken = string | undefined (41 ln)  [gen/]
- `bodySerializer.gen.ts` → type QuerySerializer = (query: Record<string, unknown>) => string (74 ln)  [gen/]
- `params.gen.ts` → type Field = (144 ln)  [gen/]
- `pathSerializer.gen.ts` → interface SerializerOptions<T> { (167 ln)  [gen/]
- `queryKeySerializer.gen.ts` → type JsonValue = null | string | number | boolean | JsonValue[] | { [key: string (111 ln)  [gen/]
- `serverSentEvents.gen.ts` → type ServerSentEventsOptions<TData = unknown> = Omit<RequestInit, "method"> & (210 ln)  [gen/]
- `types.gen.ts` → interface Client<RequestFn = never, Config = unknown, MethodFn = never, BuildUrl (91 ln)  [gen/]
- `utils.gen.ts` → interface PathSerializer { (109 ln)  [gen/]
- `sdk.gen.ts` → type Options<TData extends TDataShape = TDataShape, ThrowOnError extends boolean (1197 ln)
- `types.gen.ts` → type EventServerInstanceDisposed = { (3904 ln)
- `index.ts` → * from "./client.js" (21 ln)
- `process.ts` → function stop(proc: ChildProcess) { (31 ln)
- `server.ts` → type ServerOptions = { (134 ln)
- `client.ts` → * from "./gen/types.gen.js" (88 ln)
- `data.ts` → const message = { (32 ln)
- `client.gen.ts` → type CreateClientConfig<T extends ClientOptions = ClientOptions2> = ( (18 ln)  [v2/]
- `client.gen.ts` → const createClient = (config: Config = {}): Client => { (285 ln)  [v2/]
- `index.ts` → type { Auth } from "../core/auth.gen.js" (25 ln)  [v2/]
- `types.gen.ts` → type ResponseStyle = "data" | "fields" (202 ln)  [v2/]
- `utils.gen.ts` → const createQuerySerializer = <T = unknown>({ parameters = {}, ...args }: QueryS (289 ln)  [v2/]
- `auth.gen.ts` → type AuthToken = string | undefined (41 ln)  [v2/]
- `bodySerializer.gen.ts` → type QuerySerializer = (query: Record<string, unknown>) => string (82 ln)  [v2/]
- `params.gen.ts` → type Field = (169 ln)  [v2/]
- `pathSerializer.gen.ts` → interface SerializerOptions<T> { (167 ln)  [v2/]
- `queryKeySerializer.gen.ts` → type JsonValue = null | string | number | boolean | JsonValue[] | { [key: string (111 ln)  [v2/]
- `serverSentEvents.gen.ts` → type ServerSentEventsOptions<TData = unknown> = Omit<RequestInit, "method"> & (239 ln)  [v2/]
- `types.gen.ts` → type HttpMethod = "connect" | "delete" | "get" | "head" | "options" | "patch" |  (86 ln)  [v2/]
- `utils.gen.ts` → interface PathSerializer { (137 ln)  [v2/]
- `sdk.gen.ts` → type Options<TData extends TDataShape = TDataShape, ThrowOnError extends boolean (4497 ln)  [v2/]
- `types.gen.ts` → type ClientOptions = { (5546 ln)  [v2/]
- `index.ts` → * from "./client.js" (23 ln)
- `server.ts` → type ServerOptions = { (134 ln)

Auto-generated: 2026-05-03
