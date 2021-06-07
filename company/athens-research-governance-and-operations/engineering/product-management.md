# Product Management

Purpose

To provide recommendations on the design and engineering of the v1 Athens product.

#### Recommendations

* Athens Engineers will lead feature development.
  * Athens Engineer definition: an Athenian that has committed Clojure code to the Athens codebase.
  * If you have Clojure experience and you want to be an Athens Engineer, an admin of the GitHub organization \(Jeroen or Jeff\) will add you as a writer to the Athens repository.
  * If you do not have Clojure experience and you want to be an Athens Engineer, begin studying [Onboarding for New Clojurians](https://www.notion.so/Onboarding-for-New-Clojurians-b34b38f30902448cae68afffa02425c1) and apply to our ClojureFam program as a learner.
  * If you are enrolled in the ClojureFam program as a Learner and you already have a partner, you are on track to becoming an Athens Engineer.
* Athens Designers will lead product design.
  * Athens Designers definition: an Athenian that has contributed prototypes, mockups, logos, user stories, and other design resources.
  * If you want to become an Athens Designer, we are setting up the onboarding resources and processes. DM [Jacob Morse](https://www.notion.so/Jacob-Morse-a36866bedf804677a3e6a8725dd43b16) in the meantime.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8cdccf1b-e32d-4ef8-8d5b-d0c4a5a8ef40/Screen\_Shot\_2020-05-27\_at\_10.04.44\_AM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8cdccf1b-e32d-4ef8-8d5b-d0c4a5a8ef40/Screen_Shot_2020-05-27_at_10.04.44_AM.png)
* One project board, [A Self-Hosted Athens](https://github.com/athensresearch/athens/projects/2), will function as the central source of truth for product development.
* Issues on this project board will primarily be high-level features. Ex:

  * Search
  * Blocks
  * Links

  [https://whimsical.com/44d2rL6Epbda2dAdQppoKB](https://whimsical.com/44d2rL6Epbda2dAdQppoKB)

* Features have four phases:
  * Todo
    * The feature has not yet been assigned to anyone.
    * The feature has not yet been scoped or explored. No code has been written.
    * Athens Engineers can comment on possible rabbit holes or theories of discovery and execution. But these theories have not been validated.
  * Discovery
    * The feature has been assigned to an Athens Engineer.
    * There is still uncertainty in what needs to be done.
    * If an Athens Engineer were to give an estimate on feature completion, the confidence interval would be large \(+/- 3 days\).
  * Execution
    * There is certainty in what needs to be done.
    * "What needs to be done" can be broken down into specific issues.
    * Specific issues could be handed off to a new Clojure developer without too much additional explanation.
    * If an Athens Engineer were to give an estimate on feature completion, the confidence interval would be small \(+/- 5 hours\).
  * Done
    * For a feature to be "Done", it will have been merged into master and tested by Athenians.
    * To be merged into master, a pull request must be reviewed and approved by another Athens Engineer.
    * A pull request is often reviewed and revised a number of times before it is ready to be merged.
    * If an Athens Engineer determines that an issue or feature is not important right now, the issue can be closed \(and possibly re-opened later\).
      * The issue should be removed from the project board.
* Athens Designers will post design resources \(e.g. Figma links or user stories\) to the GitHub issue, if the feature involves UX.

## Reasoning

Athens is the first open-source product to embrace UX and end-user design. Successful open-source software has historically been for developers or enterprises. The open-source end-user products that do exist are Linux apps like OfficeLibre and GIMP, where UX has not been a driving factor.

Open-Source Product Management, which aligns design, engineering, and the self-sustainability of a project, is a new concept. Decisions \(and mistakes\) will need to be made to learn what works.

That said, the beginning of most projects look the same, regardless if they are open-source or close-source, regardless if it's engineering or design.

First, the infrastructure, architecture, and scaffolding that everything rests on needs to be established. This is typically done by principals and architects with decades of experience.

For design, the infrastructure is composed of the design system, principles, and processes.

For engineering, the infrastructure is composed of the core frameworks, libraries, and components. The core components generally inform the code organization.

Once the infrastructure is set up, it will be vastly easier for any engineers and designers to contribute.

Until the infrastructure is set up, contributing will be a challenge for both juniors and seniors alike \(and this code might get refactored anyway\).

Going forward, we hope contributions can be made in a more bottom-up and distributed way. But given the amount of uncertainty and unmapped complexity in the project, these are my recommendations for how to proceed.migrating from [https://www.notion.so/Product-Management-at-Athens-010bdaf2dcc24adba4c496516e22df5d](https://www.notion.so/Product-Management-at-Athens-010bdaf2dcc24adba4c496516e22df5d)

to be updated

