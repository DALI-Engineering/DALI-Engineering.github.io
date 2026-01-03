<aside>


## 🎯 Goals

- Understand the full product design journey
- Define a user persona
- Write functional vs technical requirements
- Generate ideas using brainstorming
- See how *constraints* actually enable creativity
</aside>

<aside>

## 🧠 Concepts

- Problem Finding / “Opportunities”
- Creating ***Personas***
- Functional & Technical Specifications
- Ideation Methods: Crazy-8s, Worst Idea Ever, Constraint Thinking
- Specification sheets
</aside>

<aside>

## 🛠 Tools / Software

- No tools used this week
</aside>

---

## Creating a Product

Most successful products are created to fill a need or solve a problem. Creating something is relatively easy, but creating something that is genuinely useful requires understanding a few critical pieces of information first.

Before designing anything, we need to clearly define:

- Problem: What needs fixing? What can be improved? How can it help them?
- User: Who is this for? Why are they the primary user?
- Requirements: What must it do? How does it achieve the solution?

Product design involves constant broadening and narrowing. We start by broadening our perspective to identify problems. Then we narrow our focus when defining personas and requirements. During ideation, we broaden again to explore many solutions, and finally converge on a smaller set of strong ideas. This process repeats multiple times to reach the best possible outcome.

---

## Finding the Problems

In this class, we will design a desk lamp together. To begin, we need to identify problems, also called opportunities, related to desk lamps.

We can do this by observing products we already own or by researching existing designs online.

A solution does not need to be groundbreaking. Designing an infinite electricity lamp would be impressive, but meaningful improvements can be as simple as improving aesthetics, usability, or how the lamp is controlled.

<aside>

Below are some problems / needs / opportunities I found with desk lamps:

- Adjustable brightness and color temperature
- Aesthetics
- Physical size

- Cost
- Limited Functionality
- Single Color
- Lack of personality or uniqueness
</aside>

---

## Creating a Persona

When designing a product, it is not enough to understand the problem alone. We must also understand who we are designing for.

A good example is medical equipment such as MRI machines. The designers of these machines are usually not doctors and may never use them personally. Still, they are responsible for ensuring the machine is safe, functional, intuitive, and not intimidating for patients.

This is where personas become useful. By understanding who will use our product, we can design more intentionally. A lamp designed for a 21 year old cyberpunk fan will be very different from one designed for a 70 year old grandma.

In practice, personas are created by interviewing users to understand their needs, habits, and pain points. These insights are then condensed into a representative primary user.

A common approach is called “interview until saturation.” This means interviewing users until the responses become repetitive. Depending on the product, this could take anywhere from 10 to over 100 interviews.

In this class, the lamp will be designed for ourselves. We will create a shared persona together.

<aside>

## Persona

- **Name:** (A fictional or placeholder name)
- **Age:** (Indicates the general age group)
- **Gender:** (Can influence design considerations)
- **Environment:** (Where the product is primarily used)
- **Habits:** (Daily behaviors that affect usage)
- **Pain points:** (Key frustrations or challenges)
- **Wishes:** (Needs and desires related to the product)
</aside>

<aside>

As designers, it is our responsibility to identify real, actionable problems. If you ask shoppers in a grocery store what their biggest problem is, many will say prices, which is not something we can easily fix. However, there are many smaller, overlooked challenges such as cart design or shelf accessibility that can be improved.

Identifying these opportunities requires observation and empathy.

</aside>

---

## Specifications

Once we understand the problem and the user, we need a clear way to guide our design decisions. This is where specifications come in.

Specifications act as a checklist that ensures our design meets user needs and stays focused throughout development.

<aside>

Specification tables help ensure our designs satisfy requirements and allow us to create testing plans and risk assessments later in the process.

</aside>

In this class, we will use a **Functional and Technical Requirements Table**.

This table separates what the product must do from how it achieves those functions. For example, if we want to control the lamp using a phone, a functional requirement would be communication between the phone and the lamp. The technical requirements might include signal strength, communication protocol, or baud rate.

<aside>

The key difference between functional and technical requirements is:

- **Functional Requirements:** What the product must do to work as intended
- **Technical Requirements:** How those functions are implemented
</aside>

Below is an example of a **Functional & Technical Requirements Table** for our lamp:

<aside>


### 🛠 Functional Requirements

| ID | Functional Requirements | MoSCoW | Method | Metric | Criteria | Justification |
| --- | --- | --- | --- | --- | --- | --- |
| 1.0.0 | Brightness Control | S | Bench-top testing | # of different light levels | ≥10 light levels | Allows smooth adjustment for different environments |
| 1.1.0 | Power Control | M | Full brightness test | Total Power Usage | ≤10W | Ensures energy efficiency |
</aside>

<aside>


### 🛠 Technical Requirements

| ID | Technical Requirements | FRs | MoSCoW | Method | Metric | Criteria | Justification |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1.0.0 | Brightness Adjustable LEDs | 1.0.0 | S | Bench-top testing | luminosity at 5cm away | ranging from 100 lumens to 600 lumens | Supports different lighting conditions |
| 1.0.1 | Addressable LEDs | 1.0.0 | S | Bench-top testing | Addressability | Yes (individually or as a strand) | Enables control via microcontroller |
</aside>

**Column Descriptions**

<aside>

### ID

Defines the component, topic group, and specific requirement using a structured numbering system.

- The first digit in the ID represents the component. For example, the lamp electronics (1.#.#) and the lamp shade (2.#.#), will have different IDs. (This digit starts from 1)
- The second digit in the ID represents the topic group. For example, if we are defining requirements about the power management of the lamp then we could ID them as 1.0.#. However, if we are talking about the heat management or the size of the electronics, then it would be a different ID such as 1.1.# and 1.2.# respectively, etc… (This digit starts from 0)
- The third digit in the ID represents each requirement. For example, if we are talking about the maximum temperature and the minimum temperature of the electrical components. These are two different requirements in the same temperate topic for the same electronics group. Therefore, their IDs would be something like: 1.1.0 and 1.1.1 respectively (This digit starts from 0).
</aside>

<aside>

### FRs

Links each technical requirement to the functional requirement it supports.

- As previously mentioned, Technical Requirements are specifications describing how can we achieve the desired function. Hence the FRs number represents the desired function that specific Technical Requirement is trying to achieve.
</aside>

<aside>

### MoSCoW

Defines priority level. (In some specification tables this is replaced by a priority number)

- **M:** Must have
- **S:** Should have
- **C:** Could have
- **W:** Won’t have
</aside>

<aside>

### Method

Describes how the requirement will be tested. For example if you are designing a phone and want to check its durability, then the method could be a “Drop Test”

</aside>

<aside>

### Metric

Defines how the test result is measured. If you do the “Drop Test” then are you going to do a visual measurement of how many cracks are there on the phone screen, are you going to measure the force induced when the phone hit the ground, or are you going to measure if the phone still works or not…

</aside>

<aside>

### Criteria

Specifies the pass condition for the requirement.

</aside>

<aside>

### Justification

Explains why the requirement is important and how it supports the user’s needs.

</aside>

---

## Ideation Process

Once requirements are defined, we can begin brainstorming solutions.

<aside>


**💡 Note: These ideas are not required to be good or satisfy all the requirements.**

</aside>

Early ideation focuses on quantity over quality. This removes pressure and encourages creative thinking. Later, ideas are refined and combined.

In this class, we will use three ideation methods.

<aside>


### 1️⃣ Crazy-8s

Each participant creates eight quick sketches, spending one minute per sketch, focused on a single requirement.

For example, if you are making a bookmark management app, a crazy-8s sketch could be a rough sketch of the home page with bookmarks.

</aside>

<aside>


### 2️⃣ Worst Idea Ever

Participants intentionally generate terrible ideas and then work backward to extract useful concepts.

For example, the bookmark management app could explode your phone when you bookmark something. Instead of exploding, maybe it gives you money or credits. What can we get out of this: engagement, excitement, etc…

</aside>

<aside>


### 3️⃣ Constraint-Driven Ideation

What would happen if our user is paralyzed? How can we design our lamp such that it is a lot more accessible to them?

What manufacturing method are we going to use? How can we design the lamp such that it can be easily 3D printed.

What material are we going to use?

</aside>

## Condensing Ideas

After ideation, we converge using a spec chart. This allows us to compare ideas against key functional requirements and identify the strongest concepts.

<aside>


**💡 Note: Ideas can be combined. A final design often includes strengths from multiple concepts.**

</aside>

Below is an example of a Spec Chart:

<aside>

### Spec Chart

| Requirements / Ideas | Lamp that blinds you in the morning | A frog lamp | A RGB clock lamp | A RGB small lamp tower |
| --- | --- | --- | --- | --- |
| Power Usage | -1 | +1 | 0 | 0 |
| Brightness | +1 | 0 | -1 | 0 |
| Color Changing | -1 | -1 | +1 | +1 |
| Size (smaller the better) | 0 | -1 | +1 | +1 |
| Price | -1 | 0 | 0 | 0 |
| Uniqueness | +1 | 0 | -1 | +1 |
| Total | -1 | -1 | -1 | 3 |
</aside>

The highest scoring concept is not always the final answer. Depending on the user and requirements, multiple ideas can be combined to create a better product.