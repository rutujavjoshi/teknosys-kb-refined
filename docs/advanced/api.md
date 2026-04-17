# API Documentation

API documentation is not about explaining—it’s about enabling.

Your reader is usually a developer who wants to integrate quickly, not read extensively.

---

## Why this matters

- Enables product integrations  
- Reduces dependency on engineering teams  
- Improves developer experience  
- Directly impacts product adoption  

---

## The core structure

Most API documentation follows a predictable pattern:


Endpoint → Request → Response → Errors


This consistency is critical.

---

## What developers expect

For every API, they look for:

- Endpoint URL  
- Method (GET, POST, etc.)  
- Parameters  
- Request example  
- Response example  
- Error handling  

---

## Example


GET /users

Response:
{
"id": 101,
"name": "John Doe"
}


---

## What makes API documentation effective

- Real examples (not placeholders)  
- Clear parameter descriptions  
- Consistent formatting  
- Explicit error messages  

---

## Common mistakes

- Explaining instead of showing  
- Missing examples  
- Inconsistent structure  
- Ignoring error scenarios  

---

## Practical guidance

- Always include request and response examples  
- Use consistent naming and formatting  
- Document edge cases and failures  
- Think: *Can a developer use this without asking questions?*  

---

## Related topics

- [Types of Documentation](../foundations/doc-types.md)  
- [Information Architecture](ia.md)  
- [Writing for Complex Systems](complex-systems.md)  

---

## Further reading

- <a href="https://swagger.io/resources/articles/" target="_blank">
API documentation best practices (Swagger)
</a>