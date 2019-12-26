# languagetool-online-editor

From LanguageTool Wiki (http://wiki.languagetool.org/google-code-in-tasks):

* Add rule / false friends (online?) editor
   * Would simplify adding rules. It would be probably working in a web browser. Options:
     * XForms: this is XML standard for forms on the web, so using it you could implement any form-based UI. The bad thing is that it is not really supported by major web browsers.
     * XML database: use some native XML database system and create a web interface to query it and modify it. This way searching for rules would be easier.
     * Use a web-based WYSIWYM (what you see is what you mean) editor to create a new editing interface.
     * Create a Java-based UI.
   * The most important functionalities would be:
     * Search for a rule (rulegroup) by id and example.
     * Display a rule (and its rulegroup in a collapsed way).
     * Modify all elements of the rule.
     * Check validity.
     * Run tests on the file (via JUnit in LanguageTool).
     * Open, Save, Save as… options in the File menu.
     * Maybe integrate a wizard to create easy rules.
