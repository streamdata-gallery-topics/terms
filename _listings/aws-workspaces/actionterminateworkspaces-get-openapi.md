---
swagger: "2.0"
x-collection-name: AWS WorkSpaces
x-complete: 0
info:
  title: AWS WorkSpaces Service API Terminate Workspaces
  version: 1.0.0
  description: Terminates the specified WorkSpaces.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=TerminateWorkspaces:
    get:
      summary: Terminate Workspaces
      description: Terminates the specified WorkSpaces.
      operationId: terminateWorkspaces
      x-api-path-slug: actionterminateworkspaces-get
      parameters:
      - in: query
        name: TerminateWorkspaceRequests
        description: An array of structures that specify the WorkSpaces to terminate
        type: string
      responses:
        200:
          description: OK
      tags:
      - Workspaces
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---