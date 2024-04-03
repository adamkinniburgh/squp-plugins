```
SELECT
    CASE
        WHEN [properties.requireAuthentication] = true
        THEN CONCAT([dashboardName], " 🔐")
        ELSE [dashboardName]
    END AS [label],
    [workspaceName] AS [sublabel],
    CASE
        WHEN [properties.enabled] = true
        THEN "success"
        ELSE "unknown"
    END AS [state],
    CONCAT("http://app.squaredup.com/openaccess/",SUBSTRING([id],9)) AS [link]
FROM dataset1
--- the following line can be used to filter out dashboards by workspace
--- or just remove it if you don't need to filter anything
WHERE [workspaceName] NOT IN ("Workspace 1", "Workspace 2")
```
