# flutter_mvvm_architecture

A project to serve as a base MVVM architecture for simple Flutter apps that requires some persistency.

## Getting Started

There are 4 layers in this architecture:
- Data (**data/**)
- Model (**models/**)
- View Model (**ui/**)
- View (**ui/**)

The naming pattern of the files are:
- Model: **models/entity.dart**
- View Model: **ui/feature/feature_viewmodel.dart**
- View: **ui/feature/feature_screen.dart**

There are some extras which aren't exactly in any of the layers above. They don't have any naming convention defined:
- Components (**/components**): Reusable Widgets through the application
- Utils (**/utils**): Classes that helps any of the layers to do some specific job
- Services (**/services**): Services that access external APIs. Naming convention is **/services/example_service.dart**
