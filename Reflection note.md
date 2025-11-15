# Reflection note

### Differences between my custom DTD and TEI_all

##### Advantages of using TEI_all

The immediate advantage of using the TEI_all scheme is that it has much greater depth than the custom DTD I have made when it comes to the **metadata description**. The structure of the <teiHeader> element and its components allows to structure the encoded document in a much clearer way.

**Easy access to documentation** when deciding how to structure the document is a great boon. It allowed me to think of elements which I had not considered at all when encoding my own DTD.

**The great variety of elements** available as part of TEI_all means that I was able to use schemes such as <msDesc> or <listPerson> to describe the document and where it can be found in detail, unlike my DTD.

##### Difficulties and inconvenients of using TEI_all

**The generalist nature of the TEI_all scheme** means that it is harder to describe the contents of the document to the extent which I would have liked to, or at least not in the manner I wanted to.

**The structure of the encoding** is sometimes strange, mandating the use of elements which seem to only be present due to the restrictions of the scheme. Uses of the element <div> had little impact on the document but was mandatory for the <p> element, for instance.

**The sheer size of the scheme** means one has less control and takes more time figuring out where which element should be included.

### Conclusion

Overall, using a scheme is better for good practices and interoperability, but it takes away granularity and precision in the encoding by restraining the way one can use XML. I would say that it is useful, but that I can see a case for customizing it.
