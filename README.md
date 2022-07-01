Introduction:

A local school has decided to put together a flashcard application, Flashcard-o-matic, to help their students study online.
Teachers will use this application to create decks of flashcards for the subjects they teach, and students will study the decks. The school needs you to build the application that the students and teachers will use.

<img width="600" alt="68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f7374726976652f696d6167652f75706c6f61642f775f313030302c685f313030302c635f6c696d69742f38616436653137623764383439323830613631396534626236396332366261612d686f6d652e706e67" src="https://user-images.githubusercontent.com/98443655/176828796-b956abe2-9369-46ac-8364-9cb037c9f529.png">




Home:
The Home screen is the first page the user sees. It is displayed at '/'.





Study:
The Study screen is displayed at /decks/:deckId/study.

<img width="500" alt="68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f7374726976652f696d6167652f75706c6f61642f775f313030302c685f313030302c635f6c696d69742f65356164616635376165663565333866346463643865376566643061356463392d73747564792d66697273742d636172642e706e67" src="https://user-images.githubusercontent.com/98443655/176829092-fcee51ed-5646-48ea-93cd-d33f3cb45ddd.png">



Next Button:
The Next button appears after the card is flipped.





Restart prompt:
When all cards are finished, a message is shown and the user is offered the opportunity to restart the deck. If the user does not restart the deck, they return to the home screen.

<img width="468" alt="68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f7374726976652f696d6167652f75706c6f61642f775f313030302c685f313030302c635f6c696d69742f35396636373261346461653939356464376266656564303461623032306237302d792d726573746172742d70726f6d70742e706e67" src="https://user-images.githubusercontent.com/98443655/176829167-e7f7f13a-f433-46fa-9271-25b8337bf14a.png">




Not enough cards:
Studying a Deck with two or fewer cards should display a Not enough cards message and a button to add cards to the deck.

Create Deck:
The Home screen has a Create Deck button that brings the user to the Create Deck screen.

<img width="500" alt="68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f7374726976652f696d6167652f75706c6f61642f775f313030302c685f313030302c635f6c696d69742f63353830366135373737616134363836323337363764386661346661386665382d6465636b2d6372656174652e706e67" src="https://user-images.githubusercontent.com/98443655/176829258-278aa62e-a675-45cb-b602-18c850c6375f.png">



Deck:
The Deck screen displays all of the information about a deck.


<img width="403" alt="68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f7374726976652f696d6167652f75706c6f61642f775f313030302c685f313030302c635f6c696d69742f66363362386265646161663337636438633332343566656265366630323735662d6465636b2e706e67" src="https://user-images.githubusercontent.com/98443655/176829308-f5bba8b4-4ded-4bde-b9eb-3ba48f5b9434.png">

Delete Card Prompt:
When the user clicks the Delete button associated with a card, a warning message is shown and the user can click OK or Cancel. If the user clicks OK, the card is deleted.


Edit Deck:
The Edit Deck screen allows the user to modify information on an existing deck.


Add Card: 
The Add Card screen allows the user to add a new card to an existing deck.


Edit Card:
The Edit Card screen allows the user to modify information on an existing card.
<img width="403" alt="68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f7374726976652f696d6167652f75706c6f61642f775f313030302c685f313030302c635f6c696d69742f63643661316630373537346266383534346230613330643435303230613237342d636172642d656469742e706e67" src="https://user-images.githubusercontent.com/98443655/176829432-74255fb6-489d-4e11-8512-58f4c31e6289.png">


