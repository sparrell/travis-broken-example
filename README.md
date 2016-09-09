# travis-broken-example

An example that will cause a build failure as Test.php is originally written
   $this->assertEquals(1+1,1);
but will pass when corrected
   $this->assertEquals(1+1,2);
