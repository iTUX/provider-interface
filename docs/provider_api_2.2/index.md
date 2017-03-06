# Provider Interface API V2.2

**OBS: <br>
Version 2.2 är fortfarande under utveckling. Dokumentationen innehåller de delar som stöds officiellt**

## Innehåll

* [Ändringar mot tidigare versioner](changelog.md)
* [Feasibility](feasibility.md)
* [Availability](availability.md)
* [Service Activation API](service_activation.md)
* [Fault Management: Link Status API](fm_linkstatus.md)
* [Övergripande](misc.md)

## Terminologi

### Access

En _Access_ definieras som en avlämningspunkt som måste aktiveras för att en slutkund skall få tjänst. Utgörs typiskt av en port i en access-switch, förbindelsen till och uttaget i bostaden.

### Feasibility

_Feasibility_ definieras som lista med _accesser_ med tillhörande data för att unikt kunna identifiera accesser (adress, lägenhetsbeteckningar etc.) och vilka tekniska tjänster som är potentiellt beställningsbara (per _access_). _Feasibility_ omfattar inte om tjänsterna är aktiva eller tillgängliga. _Feasibility_ används till säljkampanjer, täckningskartor och liknande. _Feasiblitity_ används även vid kontakt med slutkund för att identifiera vilken specifik _access_ som tjänster skall aktiveras på.

### Availability

_Availability_ definieras som aktuell status på vilka tjänster som är aktiva och vilka som går att leverera på en specifik access. _Availability_-frågor används ofta interaktivt, exempelvis under konversation med potentiell slutkund. KO kan med hjälp av _Availability_ indikera om en teknisk tjänst är "upptagen" av en annan TL.