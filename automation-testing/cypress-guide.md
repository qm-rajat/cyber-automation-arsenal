
```markdown
# Cypress Automation Guide

## Key Concepts
- cy.visit()
- cy.get()
- cy.contains()
- Assertions

## Sample Test

```javascript
describe('Login Test', () => {
  it('should login successfully', () => {
    cy.visit('/login')
    cy.get('#username').type('admin')
    cy.get('#password').type('password')
    cy.get('button').click()
  })
})