# EventStorming

# Domains
Areas of responsibility.

# Commands
Direct consequences of user action.

Can invoke an aggregate or invoke an external system.

# Aggregate
Receives commands and decides whether to execute them or not, thus producing a domain event.

# Domain Events
A Domain Event is something meaningful that happened in the domain.

Basically is the Database table responsable to save the events triggered.

From the Domain Events we create the Read Model. The UI consumes the read model.

# Subdomains
Different sub areas of responsibility.

# Bounded Contexts
Boundaries between the multiple consistent models that will coexist in your domain.

# Personas
The persons triggering the actions.
