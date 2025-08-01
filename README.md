# John-reps-
InstagramScrape
using Instasharp;
using Instasharp.Search;

var sessionId = "0123456789ABC&%!";
var client = new InstagramClient(sessionId);
var username = "hey_its_curtis";

var results = await client.SearchForProfilesAsync(username).CollectAsync();
