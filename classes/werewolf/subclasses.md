---
layout: subpage
title: Werewolf Subclasses
---

<div class="clt">
{% for subclass in site.data.werewolf_subclasses %}
  <strong>{{ subclass.name }}</strong> <em>({{ subclass.age }})</em>
  <table>
    <tr>
      <th>BRA</th><th>GRA</th><th>MET</th><th>SIZ</th><th>WIT</th><th>TEN</th><th>DIS</th><th>AUR</th><th>Talents</th><th>Powers</th>
    </tr>
    <tr>
      <td>+{{ subclass.brawn_bonus }}<br />{{ subclass.brawn_percentage }}%</td>
      <td>+{{ subclass.grace_bonus }}<br />{{ subclass.grace_percentage }}%</td>
      <td>+{{ subclass.mettle_bonus }}<br />{{ subclass.mettle_percentage }}%</td>
      <td>+{{ subclass.size_bonus }}<br />{{ subclass.size_percentage }}%</td>
      <td>+{{ subclass.wits_bonus }}<br />{{ subclass.wits_percentage }}%</td>
      <td>+{{ subclass.tenacity_bonus }}<br />{{ subclass.tenacity_percentage }}%</td>
      <td>+{{ subclass.discipline_bonus }}<br />{{ subclass.discipline_percentage }}%</td>
      <td>+{{ subclass.aura_bonus }}<br />{{ subclass.aura_percentage }}%</td>
      <td>{{ subclass.talents | join:'\n' | replace:' ','&nbsp;' | replace:'\n','<br />' }}</td>
      <td>{{ subclass.powers | join:'\n' | replace:' ','&nbsp;' | replace:'\n','<br />' }}</td>
    </tr>
  </table>
  {% assign alpha_list = subclass.subclasses %}
  <ul>
    {% for alpha_class in alpha_list %}
    <li>
      <strong>{{ alpha_class.name }}</strong> <em>({{ alpha_class.age }})</em>
      <table>
        <tr>
          <th>BRA</th><th>GRA</th><th>MET</th><th>SIZ</th><th>WIT</th><th>TEN</th><th>DIS</th><th>AUR</th><th>Talents</th><th>Powers</th>
        </tr>
        <tr>
          <td>+{{ alpha_class.brawn_bonus }}<br />{{ alpha_class.brawn_percentage }}%</td>
          <td>+{{ alpha_class.grace_bonus }}<br />{{ alpha_class.grace_percentage }}%</td>
          <td>+{{ alpha_class.mettle_bonus }}<br />{{ alpha_class.mettle_percentage }}%</td>
          <td>+{{ alpha_class.size_bonus }}<br />{{ alpha_class.size_percentage }}%</td>
          <td>+{{ alpha_class.wits_bonus }}<br />{{ alpha_class.wits_percentage }}%</td>
          <td>+{{ alpha_class.tenacity_bonus }}<br />{{ alpha_class.tenacity_percentage }}%</td>
          <td>+{{ alpha_class.discipline_bonus }}<br />{{ alpha_class.discipline_percentage }}%</td>
          <td>+{{ alpha_class.aura_bonus }}<br />{{ alpha_class.aura_percentage }}%</td>
          <td>{{ alpha_class.talents | join:'\n' | replace:' ','&nbsp;' | replace:'\n','<br />' }}</td>
          <td>{{ alpha_class.powers | join:'\n' | replace:' ','&nbsp;' | replace:'\n','<br />' }}</td>
        </tr>
      </table>
      {% assign beta_list = alpha_class.subclasses %}
      <ul>
        {% for beta_class in beta_list %}
        <li>
          <strong>{{ beta_class.name }}</strong> <em>({{ beta_class.age }})</em>
          <table>
            <tr>
              <th>BRA</th><th>GRA</th><th>MET</th><th>SIZ</th><th>WIT</th><th>TEN</th><th>DIS</th><th>AUR</th><th>Talents</th><th>Powers</th>
            </tr>
            <tr>
              <td>+{{ beta_class.brawn_bonus }}<br />{{ beta_class.brawn_percentage }}%</td>
              <td>+{{ beta_class.grace_bonus }}<br />{{ beta_class.grace_percentage }}%</td>
              <td>+{{ beta_class.mettle_bonus }}<br />{{ beta_class.mettle_percentage }}%</td>
              <td>+{{ beta_class.size_bonus }}<br />{{ beta_class.size_percentage }}%</td>
              <td>+{{ beta_class.wits_bonus }}<br />{{ beta_class.wits_percentage }}%</td>
              <td>+{{ beta_class.tenacity_bonus }}<br />{{ beta_class.tenacity_percentage }}%</td>
              <td>+{{ beta_class.discipline_bonus }}<br />{{ beta_class.discipline_percentage }}%</td>
              <td>+{{ beta_class.aura_bonus }}<br />{{ beta_class.aura_percentage }}%</td>
              <td>{{ beta_class.talents | join:'\n' | replace:' ','&nbsp;' | replace:'\n','<br />' }}</td>
              <td>{{ beta_class.powers | join:'\n' | replace:' ','&nbsp;' | replace:'\n','<br />' }}</td>
            </tr>
          </table>
          {% assign gamma_list = beta_class.subclasses %}
          <ul>
            {% for gamma_class in gamma_list %}
            <li>
              <strong>{{ gamma_class.name }}</strong> <em>({{ gamma_class.age }})</em>
              <table>
                <tr>
                  <th>BRA</th><th>GRA</th><th>MET</th><th>SIZ</th><th>WIT</th><th>TEN</th><th>DIS</th><th>AUR</th><th>Talents</th><th>Powers</th>
                </tr>
                <tr>
                  <td>+{{ gamma_class.brawn_bonus }}<br />{{ gamma_class.brawn_percentage }}%</td>
                  <td>+{{ gamma_class.grace_bonus }}<br />{{ gamma_class.grace_percentage }}%</td>
                  <td>+{{ gamma_class.mettle_bonus }}<br />{{ gamma_class.mettle_percentage }}%</td>
                  <td>+{{ gamma_class.size_bonus }}<br />{{ gamma_class.size_percentage }}%</td>
                  <td>+{{ gamma_class.wits_bonus }}<br />{{ gamma_class.wits_percentage }}%</td>
                  <td>+{{ gamma_class.tenacity_bonus }}<br />{{ gamma_class.tenacity_percentage }}%</td>
                  <td>+{{ gamma_class.discipline_bonus }}<br />{{ gamma_class.discipline_percentage }}%</td>
                  <td>+{{ gamma_class.aura_bonus }}<br />{{ gamma_class.aura_percentage }}%</td>
                  <td>{{ gamma_class.talents | join:'\n' | replace:' ','&nbsp;' | replace:'\n','<br />' }}</td>
                  <td>{{ gamma_class.powers | join:'\n' | replace:' ','&nbsp;' | replace:'\n','<br />' }}</td>
                </tr>
              </table>
            </li>
            {% endfor %}
          </ul>
        </li>
        {% endfor %}
      </ul>
    </li>
    {% endfor %}
  </ul>
  {% endfor %}
 </div>
