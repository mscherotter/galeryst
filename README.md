# galeryst
![[galeryst](https://galeryst.com)](/images/wordmark.png)

Enable any artist to create a beautiful gallery to share their artwork with the world.

## iFrame Example
Demonstration of putting a Gallery iframe on another website.  See [html](/iframe/index.html).

The Frame sends the JSON encoded object with an _id_ and _message_ property to the hosting website:

id            | message                    | Description
------------- | -------------------------- | --
wing_selected | the unique ID of the wing  | message sent when the user clicks on a wing image in the foyer
asset_clicked | the unique ID of the asset | message sent when the user clicks on an asset in one of the galleries