import { serve } from "https://deno.land/std@0.119.0/http/server.ts";

serve((req) => new Response("Hello, World!"), { port: 8000 });
console.log("Server running on http://localhost:8000");
