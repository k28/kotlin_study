KC = "kotlinc"
TARGET = "fizzbuzz"

build:
	$(KC) $(TARGET).kt -include-runtime -d $(TARGET).jar

run: build
	java -jar $(TARGET).jar

clean:
	rm *.jar

