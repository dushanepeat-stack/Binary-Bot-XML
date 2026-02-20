<?xml version="1.0" encoding="UTF-8"?>
<xml xmlns="https://developers.google.com/blockly/xml">

  <variables>
    <variable id="stake">stake</variable>
    <variable id="profit">profit</variable>
    <variable id="loss">loss</variable>
    <variable id="consecutive_loss">consecutive_loss</variable>
  </variables>

  <block type="trade" x="20" y="20">
    <field name="MARKET">volatility_25_index</field>
    <field name="CONTRACT_TYPE">rise_fall</field>
  </block>

  <block type="purchase">
    <field name="AMOUNT">5</field>
  </block>

  <block type="condition_rsi">
    <field name="PERIOD">14</field>
    <field name="LOW">30</field>
    <field name="HIGH">70</field>
  </block>

  <block type="strategy_stop">
    <field name="TAKE_PROFIT">50</field>
    <field name="STOP_LOSS">30</field>
  </block>

</xml>
