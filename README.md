```js

    <Text style={styles.blackText}>Hello From Vaibhav!</Text>
      {/* <Image source={require("./assets/favicon.png")} /> */}
      <TouchableNativeFeedback onPress={() => console.log("nav")}>
        <View
          style={{ width: 200, height: 70, backgroundColor: "dodgerblue" }}
        ></View>
        {/* <Image
          fadeDuration={1000}
          source={{
            width: 200,
            height: 300,
            uri: "https://picsum.photos/200/300",
          }}
        /> */}
      </TouchableNativeFeedback>
      <StatusBar style="auto" />

// ---------------------------------------------

      <SafeAreaView style={styles.container}>
      <Button
        title="click me"
        color="orange"
        onPress={() => console.log("button Taped")}
      />
    </SafeAreaView>
// ---------------------------------------------
 <Button
        title="click me"
        color="orange"
        onPress={() =>
          Alert.alert("My title", "My message", [
            {
              text: "yes",
              onPress: () => console.log("Yes"),
            },
            {
              text: "no",
              onPress: () => console.log("No"),
            },
          ])
        }
      />
```
