---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Holidays Is Settlement Date
  description: Is settlement date.
  version: 1.0.0
host: globalholidays.xignite.com
basePath: xGlobalHolidays.json/XigniteGlobalHolidays
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetEventsForDate:
    get:
      summary: Get Events For Date
      description: Get events for the specified date.
      operationId: postGeteventsfordate
      x-api-path-slug: geteventsfordate-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Events
      - Date
  /GetHistoricalTicksAsOfDate:
    get:
      summary: Get Historical Ticks As Of Date
      description: Returns a historical range of ticks for a security.
      operationId: postGethistoricalticksasofdate
      x-api-path-slug: gethistoricalticksasofdate-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Historical
      - Ticks
      - As
      - Of
      - Date
  /GetNextDate:
    get:
      summary: Get Next Date
      description: Get next date.
      operationId: GetNextDate
      x-api-path-slug: getnextdate-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Next
      - Date
  /GetPriorDate:
    get:
      summary: Get Prior Date
      description: Get prior date.
      operationId: GetPriorDate
      x-api-path-slug: getpriordate-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Prior
      - Date
  /GetExchangeDateTime:
    get:
      summary: Get Exchange Date Time
      description: Get exchange date time.
      operationId: GetExchangeDateTime
      x-api-path-slug: getexchangedatetime-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Exchange
      - Date
      - Time
  /IsExchangeOpenOnDate:
    get:
      summary: Is Exchange Open On Date
      description: Is exchange open on date.
      operationId: IsExchangeOpenOnDate
      x-api-path-slug: isexchangeopenondate-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Exchange
      - Open
      - "On"
      - Date
  /GetSettlementDate:
    get:
      summary: Get Settlement Date
      description: Get settlement date.
      operationId: GetSettlementDate
      x-api-path-slug: getsettlementdate-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Settlement
      - Date
  /IsSettlementDate:
    get:
      summary: Is Settlement Date
      description: Is settlement date.
      operationId: IsSettlementDate
      x-api-path-slug: issettlementdate-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Settlement
      - Date
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