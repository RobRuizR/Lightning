# Lightning Core Reference


The Reference Documentation for Lightning Core contains detailed descriptions about various concepts of Lightning Core.

## Table of Contents
<!---TOC_start--->
* [Runtime Configuration](RuntimeConfig/index.md)
* [Render Engine](RenderEngine/index.md)
  * [Render Tree](RenderEngine/RenderTree.md)
  * [Elements](RenderEngine/Elements/index.md)
    * [Positioning](RenderEngine/Elements/Positioning.md)
    * [Rendering](RenderEngine/Elements/Rendering.md)
    * [Transform](RenderEngine/Elements/Transform.md)
    * [Children](RenderEngine/Elements/Children.md)
  * [Texture Types](RenderEngine/Textures/index.md)
    * [Rectangle](RenderEngine/Textures/Rectangle.md)
    * [Image](RenderEngine/Textures/Image.md)
    * [Text](RenderEngine/Textures/Text.md)
    * [Toolbox](RenderEngine/Textures/Toolbox.md)
    * [Canvas](RenderEngine/Textures/Canvas.md)
    * [Custom](RenderEngine/Textures/Custom.md)
  * [Shaders](RenderEngine/Shaders/index.md)
    * [Dithering](RenderEngine/Shaders/Dithering.md)
    * [Fade Out](RenderEngine/Shaders/FadeOut.md)
    * [Hole](RenderEngine/Shaders/Hole.md)
    * [Inversion](RenderEngine/Shaders/Inversion.md)
    * [Light 3D](RenderEngine/Shaders/Light3D.md)
    * [Magnifier](RenderEngine/Shaders/Magnifier.md)
    * [Perspective](RenderEngine/Shaders/Perspective.md)
    * [Pixelate](RenderEngine/Shaders/Pixelate.md)
    * [Radial Gradient](RenderEngine/Shaders/RadialGradient.md)
    * [Rounded Rectangle](RenderEngine/Shaders/RoundedRectangle.md)
    * [Spinner2](RenderEngine/Shaders/Spinner2.md)
    * [Vignette](RenderEngine/Shaders/Vignette.md)
* [Components](Components/index.md)
  * [Creation](Components/CompCreation.md)
  * [Lifecycle Events](Components/LifecycleEvents.md)
  * [Component States](Components/CompStates/index.md)
    * [State Creation](Components/CompStates/StateCreation.md)
    * [State Switching](Components/CompStates/SwitchingStates.md)
    * [State Nesting](Components/CompStates/NestingStates.md)
    * [Change Events](Components/CompStates/StateChEvents.md)
* [Templates](Templates/index.md)
  * [Patching](Templates/Patching.md)
  * [Tags](Templates/Tags.md)
  * [Clipping](Templates/Clipping.md)
  * [Flexbox](Templates/Flexbox.md)
  * [Events](Templates/Events.md)
* [Handling Input](HandlingInput/index.md)
  * [Remote / Keyboard](HandlingInput/RemoteControl/index.md)
    * [Key Handling](HandlingInput/RemoteControl/KeyHandling.md)
    * [Focus](HandlingInput/RemoteControl/Focus.md)
  * [Mouse](HandlingInput/Mouse.md)
  * [Touch](HandlingInput/Touch.md)
* [Animations](Animations/index.md)
  * [Attributes](Animations/Attributes.md)
  * [Actions](Animations/Actions.md)
  * [Action Value](Animations/ActionValue.md)
  * [Value Smoothing](Animations/ValueSmoothing.md)
  * [Methods](Animations/Methods.md)
  * [Events](Animations/Events.md)
* [Transitions](Transitions/index.md)
  * [Attributes](Transitions/Attributes.md)
  * [Methods](Transitions/Methods.md)
  * [Events](Transitions/Events.md)
* [Communication](Communication/index.md)
  * [Signal](Communication/Signal.md)
  * [Fire Ancestors](Communication/FireAncestors.md)
* [Accessibility](Accessibility/index.md)
* [TypeScript](TypeScript/index.md)
  * [Components](TypeScript/Components/index.md)
    * [Template Specs](TypeScript/Components/TemplateSpecs.md)
    * [Type Configs](TypeScript/Components/TypeConfigs.md)
    * [Subclassable Components](TypeScript/Components/SubclassableComponents.md)
  * [Guidelines / Gotchas](TypeScript/GuidelinesGotchas.md)
  * [Augmentation](TypeScript/Augmentation.md)

<!---TOC_end--->