# Product and UX case

## Problem frame

Students regularly accumulate usable objects they no longer need: textbooks, electronics, household items, furniture, and supplies. Existing marketplaces make those objects visible, but visibility alone does not make a local exchange complete.

The project focused on three connected frictions:

- **Trust:** the buyer and seller are usually strangers.
- **Coordination:** discovery, negotiation, and handover often happen across different tools.
- **Cognitive load:** broad marketplaces expose more inventory and controls than a local student exchange needs.

The research question therefore became: how can interface structure and scenario order make a peer-to-peer exchange inside a student community more predictable?

## Research approach

The bachelor project combined:

- contextual research into reuse and overconsumption;
- comparative analysis of existing resale and exchange platforms;
- role and scenario modeling;
- user journey and user flow documentation;
- information architecture;
- interface prototyping;
- implementation of a working product for evaluating the proposed decisions.

The reference analysis included broad resale products and community exchange patterns. The goal was not to reproduce a competitor feature list, but to identify where an open marketplace model conflicts with a bounded campus exchange.

## Product hypothesis

The product hypothesis had two parts:

1. a bounded university context can reduce uncertainty before users communicate;
2. a short, continuous route from item discovery to handover can reduce coordination overhead.

That produced the core loop:

```mermaid
flowchart LR
    Publish["List an item"] --> Discover["Find an item"]
    Discover --> Contact["Message the owner"]
    Contact --> Agree["Agree on conditions"]
    Agree --> Handover["Meet and exchange"]
```

## Roles

Roles are contextual rather than permanent. The same authenticated student may act as:

- **Visitor** - explores the product and public information;
- **Buyer** - searches, saves, and contacts a seller;
- **Seller** - publishes and manages listings;
- **Administrator** - manages platform users and operational content.

This avoids splitting one person into separate buyer and seller accounts.

## Principal user journeys

### Discovery and purchase intent

```text
Enter marketplace
-> browse or search
-> filter the catalog
-> open an item
-> inspect seller and exchange context
-> start a conversation
-> agree on the handover
```

### Publishing an item

```text
Authenticate
-> add photos and item details
-> select category, condition, price, and handover option
-> review the listing
-> publish
-> manage the listing from the profile
```

### Communication

```text
Open item
-> contact owner
-> enter item-linked thread
-> negotiate condition, price, and meeting point
-> retain conversation history
```

## Information architecture

The product is organized into six functional groups:

1. **Access** - login, registration, session entry.
2. **Discovery** - catalog, search, filters, item detail.
3. **Selling** - create, review, publish, edit.
4. **Communication** - inbox, item-linked conversations, notifications.
5. **Identity** - own profile, other profiles, listings, favorites, reviews, activity.
6. **Trust and support** - FAQ, safety, contact, platform administration.

The architecture is intentionally more than a sitemap. Each group corresponds to a distinct user intention and a distinct data boundary.

## Interface principles

### Context before control

The interface shows the item, owner, condition, and exchange method before asking the user to act. Controls stay close to the decision they affect.

### Progressive disclosure

The catalog stays focused on comparison. Detailed seller and exchange information appears on the listing page, while operational tools appear only for authenticated owners or administrators.

### Mobile-first responsiveness

The visual system is designed to preserve the core marketplace loop on small screens. Catalog cards, navigation, forms, and message views adapt rather than simply shrink.

### Consistent visual language

Reusable buttons, inputs, cards, badges, navigation, typography, and motion patterns form a shared interface vocabulary across discovery, publishing, messaging, support, and administration.

### Real completion state

The success state is not "message sent." The intended outcome is a completed real-world exchange. This keeps handover conditions, safety, and communication inside the product model.

## What the project demonstrated

StuffSycle demonstrated that a design-led project could be carried through the full product chain:

```text
Research -> product decision -> user flow -> information architecture
-> interface system -> application architecture -> implementation -> deployment
```

The resulting application is not presented as a scaled commercial marketplace. It is a complete, deployed product prototype that implements and demonstrates the proposed interaction and system model.
