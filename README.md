# Easy Inventory

A web-based inventory management application. Built with React, Python, Flask and MongoDB.

Please read the [Project Brief](ux/Project_Brief.md) document to learn more about the client and project requirements.

[Live Preview](https://#)

![Screenshot](https://lagallia.com/wp-content/uploads/2014/04/placeholder-840x630.png "Screenshot")

#### Table of Contents
- [Strategy](#strategy)
  - [Users](#users)
  - [User Needs](#user-needs)
  - [Business Goals](#business-goals)
- [Scope](#scope)
  - [Features](#features)
  - [User Stories](#user-stories)
- [Structure](#structure)
- [Skeleton](#skeleton)
  - [Wireframes](#wireframes)
- [Surface](#surface)
  - [Fonts](#fonts)
  - [Brand Colours](#brand-colours)
  - [Design Mockups](#design-mockups)
- [Tech](#tech)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits)

## Strategy

Inventory management and product promotion.

#### Users

*Customer*

- Professional DJs
- Beginner DJs

*Admin*

- Supplier

#### User Needs

*Customer*

* Read technical specifications
* View high resolution images
* Watch promotional videos
* Download product brochures
* Contact the supplier
* Print product details

*Admin*

* Login to admin area
* Import products
* Add technical specifications
* Upload high resolution images
* Upload promotional videos
* Edit product
* Remove product
* Export products

#### Business Goals

* Simple inventory management
* Product promotion
* Data storage
* Data analytics

## Scope

Manage the inventory and display product details to customers.

#### Features

* Product search
* PDF brochure downloads
* Products filtering
* Product sorting
* Technical specifications table
* High-resolution images
* Promotional videos
* Print details
* Admin login
* CRUD (create, remove, updated and delete)
* Hosted database
* Statistics and charts
* CSV import and export

*Features to be implemented in the future:*

- Authentication

#### User Stories

Please read the [User Stories](ux/User_Stories.md) document to learn more about the features.

## Structure

Interaction design and information architecture.

#### Diagrams

*The Mind-map*

![The Mind-map](https://lagallia.com/wp-content/uploads/2014/04/placeholder-840x630.png "The Mind-map")

*Conceptual data model*

![alt text](ux/Diagrams/Conceptual_ER_Diagram.png)

#### Database

*JSON*

```json
{
  "product": {
    "title": "Product Title",
    "body_html": "Product description...",
    "created_at": "1574982882",
    "published_at": "1574983268",
    "updated_at": "1574983277",
    "vendor": "Brand name",
    "id": 241311560,
    "sku": "sku2",
    "quantity": 7,
    "price": 995,
    "images": [
      {
        "id": 850703190,
        "product_id": 241311560,
        "position": 1,
        "created_at": "1574982882",
        "updated_at": "1574983277",
        "width": 110,
        "height": 140,
        "src": "http://"
      }
    ]
  }
}

```

## Skeleton

Low fidelity wireframes with [EPICs](ux/User_Stories.md) references.

#### Wireframes

*Home View*

![Alt](https://lagallia.com/wp-content/uploads/2014/04/placeholder-840x630.png "Alt")

*List View*

![Alt](https://lagallia.com/wp-content/uploads/2014/04/placeholder-840x630.png "Alt")

## Surface

High fidelity design mockups.

#### Fonts

...links

#### Brand Colours

![Alt](https://lagallia.com/wp-content/uploads/2014/04/placeholder-840x630.png "Alt")

#### Design Mockups

*Home View*

![Alt](https://lagallia.com/wp-content/uploads/2014/04/placeholder-840x630.png "Alt")

*List View*

![Alt](https://lagallia.com/wp-content/uploads/2014/04/placeholder-840x630.png "Alt")

## Tech

- Kanban board https://trello.com/

- Diagrams made with https://cacoo.com/

## Testing

...

## Deployment

...

## Credits

...
