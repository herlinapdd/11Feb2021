# 11Feb2021
Answer

@HappyCase 
@Test01
public void testExampleWithCorrectValues() {
    String validEmail = "george.bluth@reqres.in";
    String validPassword = "georgebluth";

    //to get a response from the api
    boolean responseOfExecutingYourApiWithCorrectValues = how you get a response from the api

    Assert.assertEquals(true, responseOfExecutingYourApiWithCorrectValues);
}

@Test02
public void testExampleWithCorrectValues() {
    String validEmail = "janet.weaver@reqres.in";
    String validPassword = "janetweaver";

    //to get a response from the api
    boolean responseOfExecutingYourApiWithCorrectValues = how you get a response from the api

    Assert.assertEquals(true, responseOfExecutingYourApiWithCorrectValues);
}

@Test03
public void testExampleWithCorrectValues() {
    String validEmail = "emma.wong@reqres.inn";
    String validPassword = "emmawong";
    
    //to get a response from the api
    boolean responseOfExecutingYourApiWithCorrectValues = how you get a response from the api

    Assert.assertEquals(true, responseOfExecutingYourApiWithCorrectValues);
}


@Negative Case
@Test01
public void testExampleWithIncorrectEmail() {
    String invalidEmail = "eve@reqres.in";
    String validPassword = "eveholt";

    //to get a response from the api
    boolean responseOfExecutingYourApiWithIncorrectValues = how you get a response from the api

    Assert.assertEquals(false, responseOfExecutingYourApiWithIncorrectValues);

}


@Test02
public void testExampleWithIncorrectPassword() {
    String validEmail = "charles.morris@reqres.in";
    String invalidPassword = "charless";

    //to get a response from the api
    boolean responseOfExecutingYourApiWithCorrectValues = how you get a response from the api

    Assert.assertEquals(false, responseOfExecutingYourApiWithCorrectValues);

}

@Test03
public void testExampleWithIncorrectPasswordEmail() {
    String validEmail = "morris@reqres.in";
    String invalidPassword = "charless";

    //to get a response from the api
    boolean responseOfExecutingYourApiWithCorrectValues = how you get a response from the api

    Assert.assertEquals(false, responseOfExecutingYourApiWithCorrectValues);

}

@Test04
public void testExampleWithEmptyPassword() {
    String validEmail = "tracey.ramos@reqres.in";
    String invalidPassword = " ";

    //to get a response from the api
    boolean responseOfExecutingYourApiWithCorrectValues = how you get a response from the api

    Assert.assertEquals(false, responseOfExecutingYourApiWithCorrectValues);

}

@Test04
public void testExampleWithEmptyEmail() {
    String validEmail = " ";
    String invalidPassword = "traceyramos";

    //to get a response from the api
    boolean responseOfExecutingYourApiWithCorrectValues = how you get a response from the api

    Assert.assertEquals(false, responseOfExecutingYourApiWithCorrectValues);

}

@Test04
public void testExampleWithEmptyEmailPassword() {
    String validEmail = " ";
    String invalidPassword = "";

    //to get a response from the api
    boolean responseOfExecutingYourApiWithCorrectValues = how you get a response from the api

    Assert.assertEquals(false, responseOfExecutingYourApiWithCorrectValues);

}
