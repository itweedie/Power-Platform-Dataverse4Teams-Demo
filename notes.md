source: 1838fca4-6258-e6b8-a710-60838df81aa3
target: 5fc7b0a0-dc6e-e682-8886-bad6dac246a7
solution: Dataverse4TeamsDemo


```
.\pipelineScripts\downloadFromSource.ps1 -solutionName "Dataverse4TeamsDemo" -exportDirectory ".\demo\dataverse4TeamsDemo" -sourceEnv "1838fca4-6258-e6b8-a710-60838df81aa3" -unpackDirectory ".\demo\dataverse4TeamsDemo\unpacked"
```


```
.\pipelineScripts\releaseToTarget.ps1 -solutionName "Dataverse4TeamsDemo" -unpackDirectory ".\demo\dataverse4TeamsDemo\unpacked" -exportDirectory ".\demo\dataverse4TeamsDemo" -targetEnvironment "5fc7b0a0-dc6e-e682-8886-bad6dac246a7" -managed

```