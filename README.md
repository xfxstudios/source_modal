# source_modal
Aporte de TrinityCore en Foros del Web
http://www.forosdelweb.com/f179/aporte-window-modal-personalizable-1160996/

# Constructor #
|
|__ · WindowsInterface(String NAME_IDSelector);

# Methods #
|
|__ · init(String ICON-PATH, String TITLE, int X, int Y, int WIDTH, int HEIGHT, Object SHOW-BUTTONS, boolean VISIBLE);
|
|__ · SetWindow()
|   |
|   |__ · BackgroundColor(String COLOR);
|   |__ · Visible(boolean VISIBLE);
|   |__ · SetWidth(int WIDTH);
|   |__ · SetHeight(int HEIGHT);
|   |__ . Size(int WIDTH, int HEIGHT);
|   |__ . Border(String BORDER);
|   |__ . Resizable(boolean RESIZABLE);
|   |__ . Draggable(boolean DRAGGABLE);
|
|__ · SetTitle()
|   |
|   |__ . BackgroundColor(String COLOR);
|   |__ . FontSize(String FONT-SIZE);
|   |__ . FontFamily(String FONT-FAMILY);
|   |__ . FontWeight(String FONT-WEIGHT);
|   |__ . FontStyle(String FONT-STYLE);
|   |__ . Font(String FONT-FAMILY, String FONT-SIZE, String COLOR, String FONT-WEIGHT);
|
|__ · SetContent()
|   |
|   |__ . Message(String MESSAGE);
|   |__ . BackgroundColor(String COLOR);
|   |__ . FontSize(String SELECTOR, String FONT-SIZE);
|   |__ . FontFamily(String SELECTOR, String FONT-FAMILY);
|   |__ . FontWeight(String SELECTOR, String FONT-WEIGHT);
|   |__ . FontStyle(String SELECTOR, String FONT-STYLE);
|   |__ . Font(String SELECTOR, String FONT-FAMILY, String FONT-SIZE, String COLOR, String FONT-WEIGHT);
|   |__ . Button();
|   |   |
|   |   |__ . Add(String ID-SELECTOR, String CLASS-SELECTOR, String BUTTON-VALUE, String BUTTON-CALLBACK);
|   |
|   |__ . Position(String SELECTOR, Object CSS-SYNTAXIS)
|   |__ . Scrollable(boolean SCROLLABLE);
