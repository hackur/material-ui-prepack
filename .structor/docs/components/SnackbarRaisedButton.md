```
<Snackbar
  message="Event added to your calendar"
  action="undo"
  autoHideDuration={this.state.autoHideDuration}
  onActionTouchTap={this._handleAction}/>
//Somewhere in our code
_handleAction() {
  //We can add more code to this function, but for now we\ll just include an alert.
  alert("We removed the event from your calendar.");
};
```
<div data-reactid=".0.$=12:0.0.0.1:3"><div style="font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;border-top:none;margin-top:0px;" data-reactid=".0.$=12:0.0.0.1:3.$0"><h3 style="font-size:20px;line-height:28px;padding-top:19px;margin-bottom:13px;letter-spacing:0px;font-weight:500;color:rgba(0, 0, 0, 0.87);box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.0">Props</h3><table style="border-collapse:collapse;border-spacing:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1"><tbody data-reactid=".0.$=12:0.0.0.1:3.$0.1.0"><tr data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0.0">action</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0.1.0"><span style="color:rgba(0, 0, 0, 0.54);padding-right:24px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0.1.0.0">string</span><span data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0.1.0.1">optional</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0.1.1">The name of the action on the snackbar.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1.0">autoHideDuration</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1.1.0"><span style="color:rgba(0, 0, 0, 0.54);padding-right:24px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1.1.0.0">number</span><span data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1.1.0.1">optional</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1.1.1">The number of milliseconds to wait before automatically dismissing. If no value is specified the snackbar will dismiss normally. If a value is provided the snackbar can still be dismissed normally. If a snackbar is dismissed before the timer expires, the timer will be cleared.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2.0">message</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2.1.0"><span style="color:rgba(0, 0, 0, 0.54);padding-right:24px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2.1.0.0">string</span><span data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2.1.0.1">required</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2.1.1">The message to be displayed on the snackbar.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3.0">openOnMount</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3.1.0"><span style="color:rgba(0, 0, 0, 0.54);padding-right:24px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3.1.0.0">bool</span><span data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3.1.0.1">default: false</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3.1.1">If true, the snackbar will open once mounted.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4.0">style</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: none; box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4.1.0"><span style="color:rgba(0, 0, 0, 0.54);padding-right:24px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4.1.0.0">object</span><span data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4.1.0.1">optional</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4.1.1">Override the inline-styles of the Snackbar's root element.</p></td></tr></tbody></table></div><div style="font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:24px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;border-top:solid 1px #e0e0e0;margin-top:24px;" data-reactid=".0.$=12:0.0.0.1:3.$1"><h3 style="font-size:20px;line-height:28px;padding-top:19px;margin-bottom:13px;letter-spacing:0px;font-weight:500;color:rgba(0, 0, 0, 0.87);box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.0">Methods</h3><table style="border-collapse:collapse;border-spacing:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1"><tbody data-reactid=".0.$=12:0.0.0.1:3.$1.1.0"><tr data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$0"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$0.0">dismiss</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$0.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$0.1.0"><span data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$0.1.0.1">Snackbar.dismiss()</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$0.1.1">Hides the snackbar.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$1"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$1.0">show</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: none; box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$1.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$1.1.0"><span data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$1.1.0.1">Snackbar.show()</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$1.1.1">Shows the snackbar.</p></td></tr></tbody></table></div><div style="font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:24px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;border-top:solid 1px #e0e0e0;margin-top:24px;" data-reactid=".0.$=12:0.0.0.1:3.$2"><h3 style="font-size:20px;line-height:28px;padding-top:19px;margin-bottom:13px;letter-spacing:0px;font-weight:500;color:rgba(0, 0, 0, 0.87);box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$2.0">Events</h3><table style="border-collapse:collapse;border-spacing:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$2.1"><tbody data-reactid=".0.$=12:0.0.0.1:3.$2.1.0"><tr data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$0"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$0.0">onActionTouchTap</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$0.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$0.1.0"><span data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$0.1.0.1">function(e)</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$0.1.1">Fired when the action button is touchtapped.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$1"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$1.0">onDismiss</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$1.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$1.1.0"><span data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$1.1.0.1">function()</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$1.1.1">Fired when the snackbar is dismissed.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$2"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$2.0">onShow</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: none; box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$2.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$2.1.0"><span data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$2.1.0.1">function()</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$2.1.0.$2.1.1">Fired when the snackbar is shown.</p></td></tr></tbody></table></div></div>