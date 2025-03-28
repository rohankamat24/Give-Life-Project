export PATH_TO_FX="/home/nora/Give_Life_Project/javafx/javafx-sdk-21.0.6/lib/"
javac --module-path $PATH_TO_FX --add-modules javafx.controls,javafx.fxml,javafx.web WebApp.java
java --module-path $PATH_TO_FX --add-modules javafx.controls,javafx.fxml,javafx.web WebApp

