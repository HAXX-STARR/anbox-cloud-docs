(howto-delete-application)=
# How to delete an application

When an application is no longer needed, it can be fully removed from Anbox Cloud. Removing an application will cause all of its versions to be removed, including all of its currently active instances. Be extra careful as this might affect your users if any are still using instances of the application you want to remove.

Once you're sure you want to remove the application, you can delete it via the dashboard or the CLI.

````{tabs}

```{group-tab} CLI

Run:

    amc application delete bcmap7u5nof07arqa2ag

The command will ask for your approval before the application is removed. If you want to bypass the check, you can add the `--yes` flag to the command.
```

```{group-tab} Dashboard

On the *Applications* page, click *Delete* ( ![delete application icon](/images/icons/delete-icon.png) ) and confirm the deletion.
```
````
