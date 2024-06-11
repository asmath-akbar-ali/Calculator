## My program uses several built-in methods and functions provided by the Android framework and Kotlin language. Here are the key ones: <br/><br/>
# Android Framework Methods: 
## 1. Activity Lifecycle Methods:

○    **onCreate(savedInstanceState: Bundle?):** This is called when the activity is first created. It is where you initialize your activity and set the layout.<br/><br/>
## 2.View Methods:

○  **setOnClickListener(listener: View.OnClickListener):** Sets a listener to be called when the view is clicked.<br/><br/>
○    **setPadding(left: Int, top: Int, right: Int, bottom: Int):** Sets the padding for the view.<br/><br/>
○    **findViewById(id: Int):** Finds a view that was identified by the ID attribute from the XML layout resource.<br/><br/>
## 3.ViewCompat:

○    **ViewCompat.setOnApplyWindowInsetsListener(view: View, listener:** OnApplyWindowInsetsListener): Sets a listener to handle window insets (e.g., system bars).<br/><br/>
## 4. WindowInsetsCompat:

○    **WindowInsetsCompat.Type.systemBars():** Retrieves the insets for the system bars.<br/><br/>
## 5.AppCompatDelegate:

○    **AppCompatDelegate.setDefaultNightMode(mode: Int):** Sets the default night mode.<br/><br/>
○    **AppCompatDelegate.getDefaultNightMode():** Gets the current night mode.<br/><br/>

# Kotlin Standard Library Methods:
## 1. StringBuilder:

○  **append(value: Any?):** Appends the string representation of the specified object to this sequence.<br/><br/>
○  **clear():** Clears the contents of the StringBuilder.<br/><br/>
○  **deleteCharAt(index: Int):** Removes the character at the specified position in this sequence.<br/><br/>
○  **insert(offset: Int, str: String):** Inserts the string into this sequence at the specified position.<br/><br/>
○  **startsWith(prefix: String):** Checks if this string starts with the specified prefix.<br/><br/>
○  **contains(sequence: CharSequence):** Returns true if the sequence contains the specified char sequence.<br/><br/>
## 2. String:

○  **toDouble():** Converts the string to a Double.<br/><br/>
## 3. when Expression:

○  **when (value) { ... }:** Similar to a switch statement in other languages, used for conditional execution based on the value of an expression.<br/><br/><br/>

# Additional Methods in Your Code:
## Custom Methods:
○  **setListener():** Sets up the click listeners for the buttons.<br/><br/>
○  **toggleNightMode():** Toggles the night mode on and off.<br/><br/>
○  **setNightModeIndicator():** Sets the indicator for the night mode based on the current mode.<br/><br/>
○  **onPercentageClicked():** Handles the percentage button click.<br/><br/>
○  **onPlusMinusClicked():** Toggles the plus/minus sign.<br/><br/>
○  **onAllClearClicked():** Resets the calculator.<br/><br/>
○  **onOperatorClicked(operator: Operator):** Handles the operator button clicks.<br/><br/>
○  **onEqualsClicked():** Handles the equals button click.<br/><br/>
○  **calculate():** Performs the calculation based on the current operator.<br/><br/>
○  **onDecimalPointClicked():** Handles the decimal point button click.<br/><br/>
○  **onZeroClicked():** Handles the zero button click.<br/><br/>
○  **onDoubleZeroClicked():** Handles the double zero button click.<br/><br/>
○  **getNumericButtons():** Returns an array of numeric buttons.<br/><br/>
○  **onNumberClicked(numberText: String):** Handles numeric button clicks.<br/><br/>
○  **setInput():** Sets the input values based on the current operator.<br/><br/>
○  **clearDisplay():** Clears the display.<br/><br/>
○  **updateResultOnDisplay(isPercentage: Boolean):** Updates the display with the result.<br/><br/>
○  **updateInputOnDisplay():** Updates the input on the display.<br/><br/>
○  **getInputValue1():** Returns the first input value.<br/><br/>
○  **getInputValue2():** Returns the second input value.<br/><br/>
○  **getOperatorSymbol():** Returns the symbol of the current operator.<br/><br/>
○  **getFormattedDisplayValue(value: Double?):** Formats the display value.<br/><br/>
##     These methods collectively handle the UI interactions, input processing, and display updates for the calculator app.
