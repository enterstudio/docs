# Versandarten

Isotope eCommerce bietet dir im Core zwei Versandarten, mit denen du in Kombination viele Anwendungsfälle abdecken kannst.

## Zur Auswahl stehen:

1. <docrobot_route name="shipping-method-flat">Pauschalversand</docrobot_route>
2. <docrobot_route name="shipping-method-group">Versandgruppierung</docrobot_route>

## Generelle Informationen für jede Versandart

## Name & Typ

<table>
	<thead>
		<tr>
			<th>Einstellung</th>
			<th>Standardeinstellung</th>
			<th>Beschreibung</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Versandart-Name</td>
			<td>-</td>
			<td>Hier kannst du der Versandart einen internen Namen vergeben. Er wird im Frontend nicht angezeigt.</td>
		</tr>
		<tr>
			<td>Bezeichnung</td>
			<td>-</td>
			<td>Hier kannst du der Versandart einen externen Namen vergeben. Er wird dem Besucher im Frontend angezeigt und kann via <docrobot_route name="translations">Übersetzungen</docrobot_route> übersetzt werden.</td>
		</tr>

		<tr>
			<td>Versandart-Typ</td>
			<td>Pauschalversand</td>
			<td>Hier wählst du deine gewünschte Versandart aus.
			<br>Auswahl Möglichkeiten:
			<ul>
				<li>Pauschalversand</li>
				<li>Versandgruppierung</li>
			</ul>
			</td>
		</tr>
	</tbody>
</table>


## Versandhinweis

<table>
	<thead>
		<tr>
			<th>Einstellung</th>
			<th>Standardeinstellung</th>
			<th>Beschreibung</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Versandart-Hinweise</td>
			<td>-</td>
			<td>Hier kannst du der Versandart eine Notiz hinzufügen. Die Hinweise können in den Benachrichtigungen mitgesendet werden, indem <code>##shipping_note##</code> verwendet wird. Mehr über Simple Tokens findest du im <docrobot_route name="simple-tokens">entsprechenden Kapitel</docrobot_route>.</td>
		</tr>
	</tbody>
</table>

## Preis-Grenzwert und Steuerklassen-Anwendbarkeit

<table>
	<thead>
		<tr>
			<th>Einstellung</th>
			<th>Standardeinstellung</th>
			<th>Beschreibung</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Preis</td>
			<td>-</td>
			<td>Hier kannst du den Preis für diese Versandart eingeben und so bspw. Versandkosten auf den Kunden umwälzen. Du kannst einen fixen Wert erfassen, sowie auch positive oder negative Prozentwerte, um vom Warenkorbwert abhängige Kosten darzustellen.</td>
		</tr>
		<tr>
			<td>Steuerklasse</td>
			<td>Steuerfrei</td>
			<td>Hier kannst du eine Steuerklasse auswählen, falls auf die Kosten der Versandart Steuern erhoben werden sollen.
			<br>Auswahl Möglichkeiten:
			<ul>
				<li>Steuerfrei</li>
				<li>Aufgeteilt</li>
			</ul>
			</td>
		</tr>
		<tr>
			<td>Pauschalpreis-Berechnung</td>
			<td>Pauschal</td>
			<td>Im diesem Auswahlmenü kannst du bestimmen, ob der erfasste Preis ein Pauschalpreis darstellt oder pro Produkt bzw. pro Stück erhoben werden soll.
			<br>Auswahl Möglichkeiten:
			<ul>
				<li>Pauschal</li>
				<li>Pro Produkt</li>
				<li>Pro Stück</li>
			</ul>
			</td>
		</tr>
	</tbody>
</table>

## Konfiguration

<table>
	<thead>
		<tr>
			<th>Einstellung</th>
			<th>Standardeinstellung</th>
			<th>Beschreibung</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Länder</td>
			<td>-</td>
			<td>Hier kannst du die jeweilige Versandart in der Zugänglichkeit für bestimmte Länder einschränken. Wenn du hier nichts auswählst, steht die Versandart für alle Länder zur Verfügung.</td>
		</tr>
		<tr>
			<td>Bundesländer/Staaten/Regionen</td>
			<td>-</td>
			<td>Hier kannst du die jeweilige Versandart in der Zugänglichkeit für bestimmte Bundesländer/Staaten/Regionen einschränken. Wenn du hier nichts auswählst, steht die Versandart für alle Staaten/Regionen zur Verfügung.</td>
		</tr>
		<tr>
			<td>Postleitzahlen</td>
			<td>-</td>
			<td>Hier kannst du die jeweilige Versandart in der Zugänglichkeit für bestimmte Postleitzahlen einschränken. Wenn du hier keine komma-separierte Liste eingibst, steht die Versandart für alle Postleitzahlen zur Verfügung.</td>
		</tr>
		<tr>
			<td>Mengen-Berechnungsmodus</td>
			<td>Gesamtmenge im Warenkorb</td>
			<td>Diese Einstellung bezieht sich auf die nachfolgenden zwei Einstellungen "Minimale Anzahl" und "Maximale Anzahl" und regelt, ob die Werte für die Anzahl unterschiedlicher Produkte oder die gesamte Anzahl der Produkte im Warenkorb gelten sollen.
			<br>Auswahl Möglichkeiten:
			<ul>
				<li>Gesamtmenge im Warenkorb</li>
				<li>Menge der verschiedenen Produkte im Warenkorb</li>
			</ul>
			<docrobot_new_in_version version="2.3"><p>Dieses Feature ist neu in Isotope eCommerce 2.3</p></docrobot_new_in_version></td>
		</tr>
		<tr>
			<td>Mindestmenge</td>
			<td>0</td>
			<td>Hier kannst du eine minimale Anzahl für diese Versandart festlegen. Angewendet bedeutet das, der potenzielle Käufer kann diese Versandart erst dann nutzen, wenn er Produkte von mindestens dieser Anzahl im Warenkorb hat.<docrobot_new_in_version version="2.3"><p>Dieses Feature ist neu in Isotope eCommerce 2.3</p></docrobot_new_in_version></td>
		</tr>
		<tr>
			<td>Höchstmenge</td>
			<td>0</td>
			<td>Hier kannst du eine maximale Anzahl für diese Versandart festlegen. Angewendet bedeutet das, der potenzielle Käufer kann diese Versandart erst dann nutzen, wenn er Produkte von maximal dieser Anzahl im Warenkorb hat.<docrobot_new_in_version version="2.3"><p>Dieses Feature ist neu in Isotope eCommerce 2.3</p></docrobot_new_in_version></td>
		</tr>
		<tr>
			<td>Mindestbetrag Zwischensumme</td>
			<td>0.00</td>
			<td>Hier kannst du einen Mindestbetrag der Zwischensumme für diese Versandart festlegen. Angewendet bedeutet das, der potenzielle Käufer kann diese Versandart erst dann nutzen, wenn er Produkte von mindestens diesem Wert im Warenkorb hat.</td>
		</tr>
		<tr>
			<td>Höchstbetrag Zwischensumme</td>
			<td>0.00</td>
			<td>Hier kannst du einen Höchstbetrag der Zwischensumme für diese Versandart festlegen. Angewendet bedeutet das, der potenzielle Käufer kann diese Versandart erst dann nutzen, wenn er Produkte von maximal diesem Wert im Warenkorb hat.</td>
		</tr>
		<tr>
			<td>Mindestgewicht</td>
			<td>-</td>
			<td>Diese Einstellung kommt dann zum Tragen, wenn der <docrobot_route name="product-types">Produkttyp</docrobot_route> das Attribut für die Gewichtseingabe erlaubt. Sobald Isotope weiss, wie schwer ein Produkt ist, kann die Versandart auf das Gewicht eingeschränkt werden.</td>
		</tr>
		<tr>
			<td>Höchstgewicht</td>
			<td>-</td>
			<td>Diese Einstellung kommt dann zum Tragen, wenn der <docrobot_route name="product-types">Produkttyp</docrobot_route> das Attribut für die Gewichtseingabe erlaubt. Sobald Isotope weiss, wie schwer ein Produkt ist, kann die Versandart auf das Gewicht eingeschränkt werden.</td>
		</tr>
		<tr>
			<td>Produkttypen</td>
			<td>-</td>
			<td>Hier kannst du die jeweilige Versandart in der Zugänglichkeit für bestimmte Produkttypen einschränken. Wenn du hier nichts auswählst, steht die Versandart für alle Produkttypen zur Verfügung.</td>
		</tr>
 		<tr>
			<td>Produkttyp-Bedingungen</td>
			<td>Nur erlauben bei folgenden Produkttypen im Warenkorb</td>
			<td>Wähle aus, wie der Produkttyp-Filter angewandt werden soll.
			<br>Auswahl Möglichkeiten:
			<ul>
				<li>Nur erlauben bei folgenden Produkttypen im Warenkorb</li>
				<li>Nur erlauben wenn alle der folgenden Produkttypen im Warenkorb liegen</li>
				<li>Erlauben, wenn einer der folgenden Produkttypen im Warenkorb liegt</li>
				<li>Preis für diese Produkttypen berechnen</li>
			</ul>
			</td>
		</tr>
		<tr>
            <td>Konfigurationen</td>
            <td>-</td>
            <td>Hier kannst du die jeweilige Versandart in der Zugänglichkeit für bestimmte Shopkonfigurationen einschränken. Wenn du hier nichts auswählst, steht die Versandart für alle Shopkonfigurationen zur Verfügung. <docrobot_new_in_version version="2.2"><p>Dieses Feature ist neu in Isotope eCommerce 2.2</p></docrobot_new_in_version></td>
        </tr>
	</tbody>
</table>

## Experten-Einstellungen

<table>
	<thead>
		<tr>
			<th>Einstellung</th>
			<th>Standardeinstellung</th>
			<th>Beschreibung</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Nur für Gäste anzeigen</td>
			<td>-</td>
			<td>Hier kannst du bestimmen, ob diese Versandart nur für Gäste zur Verfügung stehen soll.</td>
		</tr>
		<tr>
			<td>Modul schützen</td>
			<td>-</td>
			<td>Im Gegensatz zu "Nur für Gäste anzeigen" kannst du hier die Versandart für bestimmte Mitgliedergruppen einschränken.</td>
		</tr>
	</tbody>
</table>

## Freigabe

<table>
	<thead>
		<tr>
			<th>Einstellung</th>
			<th>Standardeinstellung</th>
			<th>Beschreibung</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Aktiv</td>
			<td>-</td>
			<td>Hier kannst du die Versandart aktivieren bzw. deaktivieren. 
<docrobot_message type="info"><p>Jede Versandart kann aktiviert, sowie deaktiviert werden. Sie steht damit aber noch <strong>nicht</strong> automatisch im <docrobot_route name="checkout">Kassen-Modul</docrobot_route> zur Verfügung, sondern muss da zusätzlich aktiviert werden. Siehe auch entsprechendes Kapitel.</p></docrobot_message></td>
		</tr>
	</tbody>
</table>


